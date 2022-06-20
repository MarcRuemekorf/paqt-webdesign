<template>
  <div class="min-h-screen py-6 px-4 sm:px-6 lg:px-8 flex flex-col h-full space-y-6 text-lg">
    <div class="flex-shrink-0">
      <TheHeader />
    </div>
    <div class="w-full h-full flex-1">
      <div class="grid grid-cols-3 gap-6 w-full">
        <div class="col-span-3 sm:col-span-2 flex justify-center items-center bg-gray-100 border-2 border-indigo-600 h-80">
          Content
        </div>
        <div class="col-span-3 sm:col-span-1 flex justify-center items-center bg-gray-100 border-2 border-indigo-600 h-80">
          Sidebar
        </div>
      </div>
    </div>
    <div class="flex-shrink-0">
      <TheFooter />
    </div>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader'
import TheFooter from '@/components/TheFooter'
export default {
  name: 'IndexPage',
  components: {
    TheHeader,
    TheFooter
  }
}
</script>

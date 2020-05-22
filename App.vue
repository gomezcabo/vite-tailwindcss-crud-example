<template>
  <div class="bg-gray-100 h-screen">
    <header class="bg-gray-700 shadow-sm">
      <div class="max-w-6xl mx-auto py-4 px-4 sm:px-6 lg:px-8 flex w-full items-center justify-between">
        <h1 class="text-lg leading-6 font-semibold text-white">
          My CRUD example
        </h1>
        <button
          class="p-1 border-2 border-transparent text-gray-400 rounded-full hover:text-white focus:outline-none focus:text-white focus:bg-gray-700"
          aria-label="Notifications"
        >
          <svg class="h-6 w-6" stroke="currentColor" fill="none" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4" />
          </svg>
        </button>
      </div>
    </header>
    <main class="h-16">
      <div class="max-w-6xl mx-auto py-6 sm:px-6 lg:px-8">
        <ItemsTable />
      </div>
    </main>
  </div>
</template>

<script>
import ItemsTable from './components/ItemsTable.vue'
import IconEdit from './components/IconEdit.vue'

export default {
  name: 'App',
  components: {
    ItemsTable,
    IconEdit
  }
}
</script>

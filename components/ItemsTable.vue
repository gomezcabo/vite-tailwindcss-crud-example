<template>
  <div class="flex flex-col">
    <div class="-my-2 py-2 overflow-x-auto sm:-mx-6 sm:px-6 lg:-mx-8 lg:px-8">
      <div
        class="align-middle inline-block min-w-full shadow overflow-hidden sm:rounded-lg border-b border-gray-200"
      >
        <table class="min-w-full">
          <thead>
            <tr>
              <th
                class="px-6 py-3 border-b border-gray-200 bg-gray-300 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider"
              >
                Name
              </th>
              <th
                class="px-6 py-3 border-b border-gray-200 bg-gray-300 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider"
              >
                Title
              </th>
              <th
                class="px-6 py-3 border-b border-gray-200 bg-gray-300 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider"
              >
                Email
              </th>
              <th>Role</th>
              <th
                class="px-6 py-3 border-b border-gray-200 bg-gray-300 text-left text-xs leading-4 font-medium text-gray-700 uppercase tracking-wider"
              ></th>
            </tr>
          </thead>
          <tbody>
            <tr class="bg-white">
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                Bernard Lane
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                Director, Human Resources
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                bernardlane@example.com
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                pa
              </td>
              <td><IconEdit></IconEdit></td>
            </tr>
            <tr class="bg-white">
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                Bernard Lane
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                Director, Human Resources
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                bernardlane@example.com
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                pa
              </td>
              <td><IconEdit></IconEdit></td>
            </tr>
            <tr class="bg-white">
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                Bernard Lane
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                Director, Human Resources
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                bernardlane@example.com
              </td>
              <td
                class="px-6 py-4 whitespace-no-wrap text-sm leading-5 text-gray-500"
              >
                pa
              </td>
              <td><IconEdit></IconEdit></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
import IconEdit from "/components/IconEdit.vue";

export default {
  name: "ItemsTable",
  components: {
    IconEdit,
  },
};
</script>

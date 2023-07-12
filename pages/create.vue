<template>
  <Header>
    <Title>Add Book</Title>
  </Header>
  <div class="my-10 flex justify-center h-screen">
    <div
      class="w-full m-auto max-w-lg p-4 bg-white border border-gray-200 rounded-lg shadow sm:p-6 md:p-8 dark:bg-gray-800 dark:border-gray-700"
    >
      <form class="space-y-6" action="#">
        <h5 class="text-lg font-medium text-gray-900 dark:text-white">
          Add Book
        </h5>
        <div>
          <label
            for="ISBN"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >ISBN</label
          >
          <input
            type="text"
            name="isbn"
            id="isbn"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Title"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Title</label
          >
          <input
            type="text"
            name="title"
            id="title"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Subtitle"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Subtitle</label
          >
          <input
            type="text"
            name="subtitle"
            id="subtitle"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Author"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Author</label
          >
          <input
            type="text"
            name="author"
            id="author"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Published"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Published</label
          >
          <input
            type="date"
            name="published"
            id="published"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Publisher"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Publisher</label
          >
          <input
            type="text"
            name="publisher"
            id="publisher"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Pages"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Pages</label
          >
          <input
            type="text"
            name="pages"
            id="pages"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Description"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Description</label
          >
          <input
            type="text"
            name="description"
            id="description"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>
        <div>
          <label
            for="Website"
            class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
            >Website</label
          >
          <input
            type="text"
            name="website"
            id="website"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
            required
          />
        </div>





        

        <button
          type="submit"
          class="w-full text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        >
          Add
        </button>

      </form>
    </div>
  </div>
</template>

<script setup></script>

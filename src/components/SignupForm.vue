<template>
  <div class="mt-10 sm:mt-0">
    <div class="mt-5 md:mt-0 md:col-span-2">
      <div class="shadow overflow-hidden sm:rounded-md">
        <div class="px-4 py-5 bg-white sm:p-6">
          <div class="grid grid-cols-6 gap-6">
            <div class="col-span-6 sm:col-span-6">
              <label
                for="username"
                class="block text-sm font-medium text-gray-700"
                >Username</label
              >
              <input
                type="text"
                name="username"
                id="username"
                autocomplete="username"
                class="appearance-none rounded-none relative block w-full px-3 py-2 border border-gray-300 placeholder-gray-500 text-gray-900 rounded focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:z-10 sm:text-sm"
              />
            </div>

            <div class="col-span-6 sm:col-span-6">
              <label for="email" class="block text-sm font-medium text-gray-700"
                >Email</label
              >
              <input
                type="text"
                name="email"
                id="email"
                autocomplete="email"
                class="appearance-none rounded-none relative block w-full px-3 py-2 border border-gray-300 placeholder-gray-500 text-gray-900 rounded focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:z-10 sm:text-sm"
              />
            </div>

            <div class="col-span-6 sm:col-span-6">
              <label
                for="password"
                class="block text-sm font-medium text-gray-700"
                >Password</label
              >
              <input
                type="password"
                name="password"
                id="password"
                autocomplete="password"
                class="appearance-none rounded-none relative block w-full px-3 py-2 border border-gray-300 placeholder-gray-500 text-gray-900 rounded focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:z-10 sm:text-sm"
              />
            </div>
          </div>
          <div class="grid grid-cols-6 gap-6 py-5">
            <button
              type="submit"
              class="col-span-6 sm:col-span-6 inline-flex justify-center py-5 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"
            >
              Signup for Coursebox
            </button>
            <p class="col-span-6 sm:col-span-6 text-xs text-gray-600">
              By clicking “Sign up for GitHub”, you agree to our Terms of
              Service and Privacy Statement. We’ll occasionally send you account
              related emails.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style lang="scss" scoped></style>

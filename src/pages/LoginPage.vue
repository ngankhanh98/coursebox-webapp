<template>
  <div
    class="min-h-screen flex items-center justify-center bg-gray-50 py-12 px-4 sm:px-6 lg:px-8"
  >
    <div class="max-w-md w-full space-y-8">
      <div>
        <img
          class="mx-auto h-12 w-auto"
          src="../assets/imgs/logo.png"
          alt="Coursebox"
        />
        <h2 class="mt-6 text-center text-3xl font-extrabold text-gray-900">
          Welcome back.
        </h2>
      </div>
      <LoginForm />
    </div>
  </div>
</template>

<script>
import LoginForm from "../components/LoginForm";
export default {
  data() {
    return {
      username: "",
      password: "",
    };
  },
  components: {
    LoginForm,
  },
  setup() {
    return {};
  },
};
</script>

<style lang="scss" scoped></style>

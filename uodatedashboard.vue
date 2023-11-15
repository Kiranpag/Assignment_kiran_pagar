<template>
  <div>
    <div class="dashboard-header bg-blue-500 text-white p-4">
      <h1>User Management Dashboard</h1>
    </div>

    <div class="tabs flex justify-center bg-gray-200 p-4">
      <router-link to="/user-details" class="tab">User Details</router-link>
      <router-link to="/account-creation" class="tab">Account Creation</router-link>
    </div>

    <router-view />
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Your Tailwind CSS styles for Dashboard */
</style>

<template>
  <div>
    <input v-model="searchTerm" placeholder="Search by username" @input="searchUsers" class="input" />

    <table class="table">
      <!-- ... (rest of the component remains the same) -->
    </table>

    <UserReportModal v-if="selectedUser" :user="selectedUser" @close="closeReportModal" />
  </div>
</template>

<script>
import axios from 'axios';
import UserReportModal from './UserReportModal.vue';

export default {
  // ... (rest of the component remains the same)
};
</script>

<style scoped>
/* Your Tailwind CSS styles for UserDetailsTab */
</style>

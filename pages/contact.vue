<template>
  <div class="contact-form">
    <h1>Contact Us</h1>
    <form @submit.prevent="submitForm">
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" class="form-control" id="name" v-model="name" placeholder="Enter name">
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" class="form-control" id="email" v-model="email" placeholder="Enter email">
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <textarea class="form-control" id="message" v-model="message" rows="3" placeholder="Enter message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
</template>

<script>
export default {
  name: 'ContactPage',
}
</script>

<style scoped>

</style>

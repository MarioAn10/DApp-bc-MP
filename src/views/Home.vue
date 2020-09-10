<template>
  <div class="home">
    <div>
      <h1>My accounts</h1>
      <form @submit.prevent="create">
        <div class="form-group">
          <label for="name">Name of your new Account</label>
          <input
            type="email"
            class="form-control"
            id="name"
          />
        </div>
        <button type="submit" class="btn btn-primary">Create</button>
      </form>
      <hr>
      <ul>
        <li>Account 1</li>
        <li>Account 2</li>
        <li>Account 3</li>
      </ul>
    </div>
    <div>
      <h1>BC Project</h1>
      <hr />
      <h2>A starter blockchain project for Macro Proyectos</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
};
</script>

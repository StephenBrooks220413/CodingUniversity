<template>
  <div class="hello container">
    <h1 class="display-4">{{ msg }}</h1>
    <br />
    <form name="contact" netlify>
      <!-- Name input -->
      <div class="form-outline mb-4">
        <input type="text" id="form4Example1" name="name" class="form-control" />
        <label class="form-label" for="form4Example1">Name</label>
      </div>

      <!-- Email input -->
      <div class="form-outline mb-4">
        <input type="email" id="form4Example2" name="email" class="form-control" />
        <label class="form-label" for="form4Example2">Email address</label>
      </div>

      <!-- Message input -->
      <div class="form-outline mb-4">
        <textarea class="form-control" name="message" id="form4Example3" rows="4"></textarea>
        <label class="form-label" for="form4Example3">Message</label>
      </div>

      <!-- Checkbox -->
      <div class="form-check d-flex justify-content-center mb-4">
        <input
          class="form-control"
          type="date"
          name="date"
          value=""
          id="form4Example4"
        />
        <label class="form-check-label" for="form4Example4">
          Follow Up Date
        </label>
      </div>

      <!-- Submit button -->
      <button type="submit" class="btn btn-primary btn-block mb-3">
        SEND
      </button>
    </form>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello {
  padding-bottom: 120px;
  max-width: 650px;

  input {
    background-color: lightgrey !important;
    opacity: 0.3;
  }
  textarea {
    background-color: lightgrey !important;
    opacity: 0.3;
  }
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

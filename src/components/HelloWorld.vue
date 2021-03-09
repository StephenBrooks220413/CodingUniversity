<template>
  <div class="hello container">
    <!--content below top image-->
    <div class="container text-info spacer">
      <div class="row">
        <div class="col-md">
          <div class="bg"></div>
        </div>
        <div class="col-md">
          <h1>#1 Rated for Online Learning</h1>
          <h2>High Deliverable Content</h2>
          <h3>Experienced Instructors</h3>
          <h4>Learn Valuable Skills</h4>
        </div>
      </div>
    </div>
    <!--languages block-->
    <div class="angle">
      <h1 class="display-4">Languages Used</h1>
      <div class="container">
        <div class="row">
          <div class="col-md">
            <br />
            <img
              src="https://clipartart.com/images/html-logo-clipart-6.jpg"
              alt="html"
              class="max img-fluid"
            />
          </div>
          <div class="col-md">
            <br />
            <img
              src="https://1000logos.net/wp-content/uploads/2020/09/CSS-Logo.jpg"
              alt="css"
              class="max img-fluid"
            />
          </div>
          <div class="col-md">
            <br />
            <img
              src="https://www.miltonmarketing.com/wp-content/uploads/2018/04/Javascript_logo-1170x850.jpg"
              alt="javascript"
              class="max img-fluid"
            />
          </div>
          <div class="col-md">
            <br />
            <img
              src="https://res.cloudinary.com/eternitech/image/upload/$wpsize_!_cld_full!,w_400,h_400,c_scale/v1588246109/eternitech/nodejs.png"
              alt="framework"
              class="max img-fluid"
            />
          </div>
        </div>
        <br /><br />
        <!--second row-->
        <div class="row">
          <div class="col-md">
            <img
              src="https://miro.medium.com/max/3954/1*w0u2TZpEp3WfKMrlL5jTSw.png"
              alt="C#"
              class="max img-fluid"
            />
          </div>
          <div class="col-md">
            <img
              src="https://www.amittyagi.com/static/img/sql.jpg"
              alt="SQL"
              class="max img-fluid"
            />
          </div>
          <div class="col-md">
            <img
              src="https://th.bing.com/th/id/Rdba9a27a945a1fca3d1d6a9b2fa45f03?rik=wKjPIUA2HZCEkA&riu=http%3a%2f%2fwww.tridiondeveloper.com%2fwp-content%2fuploads%2f2013%2f09%2flogo-json.png&ehk=UF76lJ8jVOrNw9ZRqfS4flM%2bfeo7ylUfeut75nmI25E%3d&risl=&pid=ImgRaw"
              alt="json"
              class="max img-fluid"
            />
          </div>
          <div class="col-md">
            <img
              src="https://cms-assets.tutsplus.com/uploads/users/71/courses/419/preview_image/typescript.png"
              alt="framework"
              class="max img-fluid"
            />
          </div>
        </div>
      </div>
    </div>
    <h1 class="display-4">{{ msg }}</h1>
    <br />
    <form name="contact" netlify>
      <!-- Name input -->
      <div class="form-outline mb-4">
        <input
          type="text"
          id="form4Example1"
          name="name"
          class="form-control"
        />
        <label class="form-label" for="form4Example1">Name</label>
      </div>

      <!-- Email input -->
      <div class="form-outline mb-4">
        <input
          type="email"
          id="form4Example2"
          name="email"
          class="form-control"
        />
        <label class="form-label" for="form4Example2">Email address</label>
      </div>

      <!-- Message input -->
      <div class="form-outline mb-4">
        <textarea
          class="form-control"
          name="message"
          id="form4Example3"
          rows="4"
        ></textarea>
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
@import "../assets/styles.scss";
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

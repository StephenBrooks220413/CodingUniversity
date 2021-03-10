<template>
  <div id="nav">
    <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
      <div class="container-fluid">
        <img class="navbar-logo" alt="Vue logo" src="./assets/logo.png" />
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/about"
                >About</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/resources"
                >Resources</router-link
              >
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdownMenuLink"
                role="button"
                data-mdb-toggle="dropdown"
                aria-expanded="false"
              >
                Contact
              </a>
              <ul
                class="dropdown-menu"
                aria-labelledby="navbarDropdownMenuLink"
              >
                <li><a class="dropdown-item" href="#">TeamChat</a></li>
                <li><a class="dropdown-item" href="#">Support</a></li>
                <li>
                  <a class="dropdown-item" href="#">Student(s)</a>
                </li>
              </ul>
            </li>
          </ul>
          <router-link class="nav-link active" to="/school"
            >Profiles</router-link
          >
        </div>
      </div>
    </nav>
  </div>
  <router-view />
</template>

<script>
import * as mdb from "mdb-ui-kit";

export default {
  mdb
};
</script>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding-bottom: 60px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.navbar-logo {
  width: 30px;
}
</style>

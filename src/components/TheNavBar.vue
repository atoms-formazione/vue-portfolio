<template>
  <header>
    <div class="container">
      <div class="nome">{{ firstName }} {{ lastName }}</div>
      <div class="navBar">
        <nav>
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#work">Work</a>
        </nav>
      </div>
      <div class="socialM">
        <img
          src="src/components/icons/medium-4 1.svg"
          alt="img"
          class="iconNav1"
        />
        <img
          src="src/components/icons/behance-2 1.svg"
          alt="img"
          class="iconNav2"
        />
        <img
          src="src/components/icons/twitter-6 1.svg"
          alt="img"
          class="iconNav3"
        />
      </div>
    </div>
  </header>
  <!--  <div class="navBar">
    <p class="name">John Doe</p>
    <div class="nav-bar">
      <p>Home</p>
      <p>About</p>
      <p>Work</p>
    </div>
    <div class="iconNav">
      <img
        src="src/components/icons/medium-4 1.svg"
        alt="img"
        class="iconNav1"
      />
      <img
        src="src/components/icons/behance-2 1.svg"
        alt="img"
        class="iconNav2"
      />
      <img
        src="src/components/icons/twitter-6 1.svg"
        alt="img"
        class="iconNav3"
      />
    </div>
  </div> -->
  <!-- 
    <p>{{ firstName }} {{ lastName }}</p>

    <div class="iconNav">
      <img
        src="src/components/icons/medium-4 1.svg"
        alt="img"
        class="iconNav1"
      />
      <img
        src="src/components/icons/behance-2 1.svg"
        alt="img"
        class="iconNav2"
      />
      <img
        src="src/components/icons/twitter-6 1.svg"
        alt="img"
        class="iconNav3"
      />
    </div>
  </div> -->
</template>
<script setup lang="ts">
import { ref } from "vue";
const firstName = ref("John");
const lastName = ref("Doe");
</script>
<style>
.container {
  position: relative;
  display: flex;
  justify-content: space-between;
  margin: 1rem;
  align-items: center;
  font-family: "Poppins";
  font-style: normal;
  color: #03045e;
}
.nome {
  font-weight: 600;
  padding: 0px 40px;
}
.navBar a {
  margin: 20px;
  text-decoration: none;
  cursor: pointer;
}
.socialM img {
  margin: 10px;
  cursor: pointer;
}
/* .navBar {
  display: flex;
  justify-content: space-between;
} */
.name {
  /* John Doe */
  padding-left: 50px;
  width: 114px;
  height: 36px;
  left: 97px;
  top: 34px;

  font-family: "Poppins";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 36px;
  /* identical to box height */

  /* Dark Blue */
  color: #03045e;
}

.nav-bar {
  display: flex;
  justify-content: space-between;

  width: 276px;
  height: 27px;
  left: 582px;
  top: 37px;
}
.containerNavBar p {
}

.nav-bar p {
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
}
/* .iconNav1 {
  position: absolute;
  width: 26px;
  height: 15.05px;
  left: 1201px;
  top: 42px;
}
.iconNav2 {
  position: absolute;
  width: 26px;
  height: 16.1px;
  left: 1256px;
  top: 42px;
}
.iconNav3 {
  position: absolute;
  width: 26px;
  height: 17.79px;
  left: 1311px;
  top: 41px;
} */
</style>

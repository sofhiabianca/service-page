<template>
  <div id="app">
    <nav>
      <button @click="toggleMenu" :class="{ 'active': isMenuOpen }">
        <span></span>
        <span></span>
        <span></span>
      </button>
      
      <ul v-if="isMenuOpen" class="menu-items">
        <li><router-link to="/" exact-active-class="active">Home</router-link></li>
        <li><router-link to="/about" exact-active-class="active">About</router-link></li>
        <li><router-link to="/contact" exact-active-class="active">Contact</router-link></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    }
  }
}
</script>

<style scoped>
nav {
  position: relative;
  display: inline-block;
}

.menu-button {
  cursor: pointer;
  padding: 10px;
  background-color: transparent;
  border: none;
}

.menu-button span {
  display: block;
  width: 20px;
  height: 2px;
  background-color: #333;
  margin-bottom: 5px;
}

.active .menu-button span:nth-child(1) {
  transform: translateY(5px) rotate(45deg);
}

.active .menu-button span:nth-child(2) {
  opacity: 0;
}

.active .menu-button span:nth-child(3) {
  transform: translateY(-5px) rotate(-45deg);
}

.menu-items {
  position: absolute;
  top: 60px;
  left: 0;
  background-color: white;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  z-index: 1000;
}

.menu-items li {
  list-style-type: none;
  padding: 15px;
  border-bottom: 1px solid #ccc;
}

.menu-items li:last-child {
  border-bottom: none;
}

.menu-items a {
  color: #333;
  text-decoration: none;
}

.menu-items a:hover {
  text-decoration: underline;
}
</style>

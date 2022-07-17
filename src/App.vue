<template>
  <div>
    <menu-bar></menu-bar>
    <h1>{{ message }}</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia nihil
      perspiciatis, architecto dolor voluptatibus non est iure nam modi,
      mollitia deserunt sint? Facere nulla, ullam itaque consectetur
      consequuntur impedit quos!
    </p>
    <the-footer></the-footer>
  </div>
</template>

<script>
import MenuBar from "./components/MenuBar"
import TheFooter from "./components/TheFooter"

export default {
    name: "App",
    components: {
        MenuBar,
        TheFooter
    },
    data() {
        return {
            message: "Hello Vue Router"
        }
    }
}
</script>


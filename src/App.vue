<template>
  <nav>
    <h4 class="text-xl">menu</h4>
    <ul>
      <li><router-link class="text-red-600 underline" to="/">src/pages/index.vue</router-link></li>
      <li>
        <router-link class="text-red-600 underline" to="/flex-direction-et-wrap"
          >Flex <code class="font-mono">direction</code> et <code class="font-mono">wrap</code></router-link
        >
      </li>
      <li>
        <router-link class="text-red-600 underline" to="/flex-grow-shrink-basis"
          >Flex <code class="font-mono">grow shrink</code> et <code class="font-mono">basis</code></router-link
        >
      </li>
      <li>
        <router-link class="text-red-600 underline" to="/flex-justify-align-content-items"
          >Exo Flex <code class="font-mono">justify/align</code> et <code class="font-mono">content/items</code></router-link
        >
      </li>
    </ul>
  </nav>
  <router-view class="m-2 border-2 p-2" />
</template>
<script>
export default {
  name: "App",
  components: {},
};
</script>

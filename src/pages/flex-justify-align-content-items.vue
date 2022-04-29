<template>
  <section class="relative">
    <h1 class="text-2xl">
      Exo Flex <code class="font-mono">justify/align</code><br />
      et <code class="font-mono">content/items</code>
    </h1>

    <h2 class="text-xl">Justify Content :</h2>
    <!-- https://tailwindcss.com/docs/justify-content -->
    <list-items class="flex flex-wrap justify-start" />

    <h2 class="text-xl">Align Content :</h2>
    <!-- https://tailwindcss.com/docs/align-content -->
    <list-items class="flex flex-wrap content-center" />

    <h2 class="text-xl">Align Items :</h2>
    <!-- https://tailwindcss.com/docs/align-items -->
    <list-items class="flex flex-wrap items-start" />

    <div class="relative z-10 bg-yellow-200 bg-opacity-50">
      <strong>Travail :</strong> duliquez le composant "list-items" ci-dessus (Maj+Alt+fléche haut ou bas) et complétez les classes TW pour
      fixer les aligments pour qu'ils correspondent à l'exemple en tranparence
      <ul class="list-inside list-disc">
        <li><a class="text-blue-700" href="https://tailwindcss.com/docs/justify-content">Justify Content</a></li>
        <li><a class="text-blue-700" href="https://tailwindcss.com/docs/align-content">Align Content</a></li>
        <li><a class="text-blue-700" href="https://tailwindcss.com/docs/align-items">Align Items</a></li>
      </ul>
    </div>

    <div class="absolute top-[-2px] left-[-2px] h-full w-full opacity-50">
      <img class="h-[3384px] w-[326px]" src="../assets/flex-justify-align-content-items.png" alt="" />
    </div>
  </section>
</template>

<script>
import listItems from "../components/list-items-fix-w-et-h-auto.vue";
export default {
  components: { listItems },
};
</script>
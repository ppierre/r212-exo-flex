<template>
  <section class="relative">
    <h1 class="text-2xl">Exo Flex direction et warp</h1>
    <list-items class="" /><!--block-->
    <list-items class="flex" /><!-- flex-row flex-nowrap -->
    <list-items class="flex flex-wrap" /><!-- flex-row -->

    <p class="relative z-10 bg-yellow-200 bg-opacity-50">
      <strong>Travail :</strong> duliquez le composant "list-items" ci-dessus (Maj+Alt+fléche haut ou bas) et complétez les classes TW pour
      fixer les axes de "flex" pour qu'ils correspondent à l'exemple en tranparence
    </p>

    <div class="absolute top-[-2px] left-[-2px] h-full w-full opacity-50">
      <img class="h-[2576px] w-[324px]" src="../assets/flex-direction-et-wrap.png" alt="" />
    </div>
  </section>
</template>

<script>
import listItems from "../components/list-items-fix-hw.vue";
export default {
  components: { listItems },
};
</script>
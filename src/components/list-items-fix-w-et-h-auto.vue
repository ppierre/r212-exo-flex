<template>
  <div class="m-1 box-content h-48 w-72 overflow-hidden border-2 border-orange-900 bg-slate-300">
    <div v-for="n in 7" :key="n" class="h-auto w-16 flex-none border-2 border-orange-600 bg-slate-200 p-1">item {{ n }}</div>
  </div>
</template>
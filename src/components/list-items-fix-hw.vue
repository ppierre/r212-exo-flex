<template>
  <div class="m-1 box-content h-32 w-64 overflow-hidden border-2 border-orange-900 bg-slate-300 p-4">
    <div v-for="n in 7" :key="n" class="h-16 w-16 flex-none border-2 border-orange-600 bg-slate-200 p-1">item {{ n }}</div>
  </div>
</template>
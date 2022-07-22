<script setup>
import {counter} from "@/stores/counterStore";
</script>

<template>
  <div>
    <p>
      About Page. The current count is {{counter.count}}
    </p>
  </div>
</template>

<template>
  <div class="dropdown"></div>
</template>

<script lang="ts">
import { Vue, Prop, Component } from "vue-property-decorator";
@Component
export default class Dropdown extends Vue {
  @Prop() private title!: String;
}
</script>

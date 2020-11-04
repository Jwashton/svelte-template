<script lang="ts">
  export let name: string;
</script>

<style lang="scss">
  $flavor: #af4fbb;

  .name {
    color: $flavor;
  }
</style>

<h1>Hello <span class="name">{name}</span>!</h1>

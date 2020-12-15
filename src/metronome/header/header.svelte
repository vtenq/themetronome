<script>
  import Signature from './signature.svelte';
  import Subdivision from './subdivision.svelte';
  import Automate from './automate.svelte';
</script>

<style lang="scss" global>
  .header {
    align-items: center;
    display: flex;
    justify-content: space-between;
    margin-top: 16px;

    & > * {
      flex: 0 0 80px;
    }
  }
</style>

<div class="header">
  <Signature/>
  <Subdivision/>
  <Automate/>
</div>

<script lang="ts">
  import Bars from './bars.svelte';
  import Meta from './meta.svelte';

  import Header from './header/header.svelte';
  import Controls from './controls/controls.svelte';
</script>

<style lang="scss" global>
  @import 'theme';

  #themetronome {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
    max-width: 600px;
    margin: 0 auto;
    padding: 16px;
    width: 100%;

    @media (min-width: 600px) {
      border: 3px solid $gray-900;
      border-radius: 16px;;
    }
  }
</style>

<main id="themetronome">
  <div class="group-top">
    <Bars/>
    <Meta/>
    <Header/>
  </div>
  <div class="group-buttom">
    <Controls/>
  </div>
</main>

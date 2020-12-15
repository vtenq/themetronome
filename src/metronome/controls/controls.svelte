<script>
  import Knob from './knob.svelte';
  import Play from 'src/icons/play.svg';
  import Pause from 'src/icons/pause.svg';
</script>

<style lang="scss" global>
  @import 'theme';

  .controls {
    align-items: flex-end;
    display: flex;
    justify-content: space-between;

    button {
      background-color: $gray-900;
      border: none;
      flex: 0 0 auto;
      height: 50px;
      width: 50px;
    }
  }
</style>

<div class="controls">
  <button>
    <Play/>
  </button>
  <Knob/>
  <button>
    <!-- <Pause/> -->
  </button>
</div>

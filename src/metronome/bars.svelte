<style lang="scss" global>
  @import 'theme';

  .bars {
    display: flex;
    height: 60px;

    .bar {
      background-color: $gray-900;
      border-radius: $border-radius;
      flex: 1 1 auto;
      height: 100%;
    }

    .bar + .bar {
      margin-left: 8px;
    }
  }
</style>

<div class="bars">
  <div class="bar"></div>
  <div class="bar"></div>
  <div class="bar"></div>
  <div class="bar"></div>
</div>

<script>
  export let prevHref;
  export let prevLabel;
  export let nextHref;
  export let nextLabel;
</script>

<div class="nav-bottom">
  <a class="button" href="{prevHref}">&lt; {prevLabel}</a>
  {#if nextHref}
    <a class="button" href="{nextHref}">{nextLabel} &gt;</a>
  {/if}
</div>

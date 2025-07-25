<script>
  import Wrapper from "./Wrapper.svelte";
</script>

<Wrapper let:foo>
  <div class:foo slot="title" let:foo>title2</div>
  <div class:foo>{foo}</div>
</Wrapper>

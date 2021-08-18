<script lang="ts">
import Button from "./components/Button.svelte";

</script>

<div class="calculadora">
  <Button texto ="7" />
  <Button texto ="8" />
  <Button texto ="9" />
</div>

<style>
  .calculadora {
    height: 220px;
    
    display: flex;
    flex-direction: column;

  }

</style>
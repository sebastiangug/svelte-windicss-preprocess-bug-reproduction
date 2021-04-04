<script>
  let isRed = true;
</script>

<svelte:head>
  <title>Svelte + Sveasy + Windicss</title>
</svelte:head>

<button class="bg-red-500
text-white p-5
">
Multiline
</button>

<div class:bg-red-500={isRed}>
class directive
</div>

<div class={isRed ? 'bg-red-500': 'bg-green-400'}>
  function
</div>

<style>

</style>

<script>
  let name = "Nora";
</script>

{#if name === 'Nora'}
  <p>{name} - What a beautiful name.</p>
{/if}

{#if name === 'Nora'}
  <p>{name} - What a beautiful name.</p>
{:else if name === 'Linda'}
  <p>{name} - I like that name</p>
{:else}
  <p>{name} - The name is also beautiful.</p>
{/if}

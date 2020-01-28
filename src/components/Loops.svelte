<script>
  let names = [
    { id: "1", name: "Nora" },
    { id: "2", name: "Linda" },
    { id: "3", name: "Helga" }
  ];
</script>

<h1>Beautiful names</h1>

<ul>
  {#each names as currentName, index}
    <li>
      <a
        target="_blank"
        href="https://en.wikipedia.org/wiki/{currentName.name}_(name)">
        {currentName.name}
      </a>
    </li>
  {/each}
</ul>

<script>
  let shares = 3;
  let threshold = 2;
  let secret = `super secret text`;
  $:
</script>

<input type="number" bind:value={shares} />
<input type="number" bind:value={threshold} />

<textarea bind:value={secret} />

<p>Hello {shares || "stranger"}!</p>

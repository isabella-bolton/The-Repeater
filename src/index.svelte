<script>
let text = ""
</script>

<label>
    Write Something:
    <input type="text" bind:value={text}>
</label>

<p>You said: {text}</p>
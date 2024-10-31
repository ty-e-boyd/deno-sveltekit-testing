<script lang="ts">
    let count = $state(0);
</script>

<h1>Welcome to SvelteKit</h1>
<p>
    Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the
    documentation
</p>

<br />

<p>
    You have pressed <button
        class="font-bold cursor-pointer"
        onclick={() => {
            count++;
        }}>THIS TEXT</button
    >
    a total of {count} times
</p>

<br />

<p>Adding this for the commit</p>
<p>Adding this for the commit, but a second time.</p>


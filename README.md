Reproduction

```
	<h1 class="disable-select">
		{#if visible}
			<a
				on:click={async () => {
					visible = !visible;
				}}
			>😀</a>
		{:else}
			<a
				on:click={async () => {
					visible = !visible;
				}}
			>😑</a>
		{/if}
	</h1>
```

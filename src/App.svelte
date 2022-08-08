<script>
import Nested from './Nested.svelte';
	// let name = 'world';
  // let src = 'https://svelte.dev/tutorial/image.gif';
  // let string = 'this string contains some <strong>HTML!!!</strong>';
  let count = 0;

	function incrementCount() {
	count += 1;
	}
  
</script>

<style>
  /* p {
      color: purple;
      font-family: 'Comic Sans MS', cursive;
      font-size: 2em;
    } */
</style>

<!-- <h1>Hello {name.toUpperCase()}!</h1> -->

<!-- <img src={src} alt="Image goes here">

<p>This is a paragraph.</p>
<p>{@html string}</p> -->

Clicked {count} {count === 1 ? 'time' : 'times'}
<button on:click={incrementCount}>Count</button>
<Nested/>



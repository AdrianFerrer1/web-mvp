<script>
	import { goto } from "$app/navigation";

    let email = "";
    let password = "";
    
</script>
<label>
    <p class={email ? "above" : "center"}>Email</p>
    <input bind:value={email} type="email" placeholder="Email"/>
</label>
<label>
    <p class={password ? "above" : "center"}>Contraseña</p>
    <input bind:value={password} type="password" placeholder="Contraseña"/>
</label>

<button on:click={() => goto("/orbital-ceu")}>SUBMIT</button>
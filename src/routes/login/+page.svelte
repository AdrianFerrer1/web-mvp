<script>
	import { goto } from "$app/navigation";

    let email = "";
    let password = "";
    
</script>
<label>
    <p class="E-mail">Esto es el correo</p>
    <input bind:value={email} type="email" placeholder="Email"/>
</label>
<label>
    <p class={password ? "above" : "center"}>Contraseña</p>
    <input bind:value={password} type="password" placeholder="Contraseña"/>
</label>

<button on:click={() => goto("/orbital-ceu")}>SUBMIT</button>
<style>
    .E-mail{
        background-color: red;

    }
</style>
<script>
	import { goto } from "$app/navigation";

    let email = "";
    let password = "";

    let background = "black";
    
</script>

<div class="color" style:background-color={background} style:font-family="Orbitron">
    <div id="logo">
        <img class="pequeña" src="/Logo.png" alt="logo orbital ceu"/>
    </div>
        
    <label>
        <p class="E-mail">Usuario</p>
        <input class="contemail" bind:value={email} type="email" placeholder="Email"/>

    </label>
    <label>
        
        <p class="password">Contraseña</p>
        <input class="contpass" bind:value={password} type="password" placeholder="Contraseña"/>
    </label>
        <button id="boton" on:click={() => goto("/orbital-ceu")}>SUBMIT</button>

</div>
<style>
    .E-mail{
        position: absolute;
        top: 28%;
        left: 64.4%;
        transform: translate(-50%, -50%);
        font-size: 46px;
        color: white;
    }
        
    
    .contpass{
        position: absolute;
        top: 59%;
        left: 72.9%;
        transform: translate(-50%, -50%);
        height: 5%;
        width: 27%;
    }
    
    .contemail{
        position: absolute;
        top: 40%;
        left: 72.9%;
        transform: translate(-50%, -50%);
        height: 5%;
        width: 27%;
        
    }
    .password{
        font-size: 500px;
        position: absolute;
        top: 47%;
        left: 67.2%;
        transform: translate(-50%, -50%);
        font-size: 46px;
        color: white;
        
    }
    
    .pequeña{
        position: absolute;
       top: 25%;
       left: 10%;
       width: 45%;
    }
    #boton{
        top: 66%;
        left: 59.2%;
        position: absolute;
      /* margin-top: 860px;
      margin-left: 1420px; */
      width: 7%;
      height: 3%;
      font-size: 22.8px;
    }
    .color{
        height: 100%;
    }
    *{
        font-size: 37.8px;
        font-weight: 300;
    }
    
</style>
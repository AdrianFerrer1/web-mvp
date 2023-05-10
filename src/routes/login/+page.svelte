<script>
	import { goto } from "$app/navigation";

    let email = "";
    let password = "";
   

    
</script>

<body>
<div id="logo">
<img class="pequeña" src="/Logo.png"/>
<div/>

<label>
    <p class="E-mail">Usuario</p>
    <input class="contemail" bind:value={email} type="email" placeholder="Email"/>

</label>
<label>
    
    <p class="password">Contraseña</p>
    <input class="contpass" bind:value={password} type="password" placeholder="Contraseña"/>
</label>
<div id="boton">
<button on:click={() => goto("/orbital-ceu")}>SUBMIT</button>
</div>
</body>
<style>
    .E-mail{
      
        position: absolute;
        top: 30%;
        left: 60.3%;
        transform: translate(-50%, -50%);
        font-size: 46px;
    }
        
    
    .contpass{
       
        position: absolute;
        top: 57%;
        left: 64.4%;
        transform: translate(-50%, -50%);
        transform: scale(3);
        
    }
    
    .contemail{
        position: absolute;
        top: 40%;
        left: 64.5%;
        transform: translate(-50%, -50%);
        transform: scale(3);
    }
    .password{
        position: absolute;
        top: 47%;
        left: 62.2%;
        transform: translate(-50%, -50%);
        font-size: 46px;
        
    }
  
    *{
        font-family: "Orbitron"
           
    }
    body{
        
    }
    
    .pequeña{
       margin-top: 250px;
       margin-left: 150px;
       width: 1000px;
    }
    #boton{
      margin-top: 860px;
      margin-left: 1420px;
      transform: scale(1);
    }
    
</style>
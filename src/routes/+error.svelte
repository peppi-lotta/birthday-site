<div class="content">
    <h1>404 Sivua ei löydy</h1>
    <p>Palaa takaisin etusivulle senkin tyhmeliini >:(. Ei täälä ole muuta</p>
    <a href=".">Etusivulle</a>
</div>

<style lang="scss">
    .content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        flex: 1;
        z-index: 1;
        text-shadow: 2px 2px 10px #100122;
        backdrop-filter: blur(8px);
        padding: 2px;
    }
    a {
        border: 2px solid whitesmoke;
        border-radius: 5px;
        padding: 10px 20px;
        color:whitesmoke;
        text-decoration: none;
        &:hover {
            background-color: whitesmoke;
            color: black;
        }
    }
</style>

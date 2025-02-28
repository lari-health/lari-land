<div class="wrap">
    <div class="hero">
        <h1>Managing health appointments doesn't have to be difficult.</h1>
        <p>We make it easy to manage your appointments so you can focus on what matters.</p>
        <a class="bt" href="#how">Let's go</a>
    </div>
    <div id="how">
        <h1>How do we do it?</h1>
    </div>
</div>

<style>
    .wrap {
        height: 100vh;
        width: 100vw;
        overflow-y: scroll;
        overflow-x: hidden;
    }

    .hero {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        color: white;
        flex-direction: column;
        height: 100vh;
        width: 100vw;
        background: linear-gradient(0deg, rgb(31, 31, 31) 00%, rgba(31, 31, 31, .4) 70%, rgba(0, 0, 0, 0.7)),
                url('/hallway.jpg');
        background-size: cover;
    }

    .hero > h1 {
        padding: 0;
        margin: 0;
    }

    .bt {
        background-color: rgb(76, 81, 158);
        text-decoration: none;
        color: white;
        padding: .5em;
        border-radius: 5px;
        transition: 300ms ease-in-out;
    }

    .bt:hover {
        background-color: rgb(74, 71, 130);
        color: rgb(201, 201, 201);
        transition: 200ms ease-in-out;
    }

</style>
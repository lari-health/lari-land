<script>
</script>

<div class="wrap">
    <a href="/"><img src={'/lari.svg'} width="115" height="48" alt="Lari Homepage" /></a>
    <div class="actions">
        <a href="/contact">Contact</a>
        <a href="/about">About</a>
        <a class="bt-log" href="/login">Log in</a>
    </div>
</div>
    

<style>
    .wrap {
        --padding-left-right: 3vw;
        background-color: rgba(124, 124, 124, 0.8);
        backdrop-filter: blur(20px);
        height: 7vh;
        width: calc(100vw - 2 * var(--padding-left-right));
        position: fixed;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        top: 0;
        padding-left: var(--padding-left-right);
        padding-right: var(--padding-left-right);
        overflow: hidden;
    }

    .actions {
        display: flex;
        flex-direction: row;
        justify-content: right;
        gap: 3em;
        width: 50vw;
        align-items: center;
    }

    .actions > a {
        text-decoration: none;
        color: white;
        border-radius: 5px;
    }

    .actions > a:hover {
        color: rgb(201, 201, 201);
        transition: 200ms ease-in-out;
    }

    .bt-log {
        background-color: rgb(76, 81, 158);
        text-decoration: none;
        color: white;
        padding: .5em;
        border-radius: 5px;
        transition: 300ms ease-in-out;
    }

    .bt-log:hover {
        background-color: rgb(74, 71, 130);
        color: rgb(201, 201, 201);
        transition: 200ms ease-in-out;
    }
</style>
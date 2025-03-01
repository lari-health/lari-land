<script>
    import { FontAwesomeIcon } from '@fortawesome/svelte-fontawesome'
    import { faBell, faClipboard, faChartLine, faCircleNodes } from '@fortawesome/free-solid-svg-icons'
    import { config } from '@fortawesome/fontawesome-svg-core'
  
    import '@fortawesome/fontawesome-svg-core/styles.css' // Import the CSS
    config.autoAddCss = false // Tell Font Awesome to skip adding the CSS automatically since it's being imported above
  </script>
  
<div class="wrap">
    <div class="hero">
        <h1>Managing health appointments doesn't have to be so difficult.</h1>
        <p>We make it easy to manage your appointments so you can focus on what matters.</p>
        <a class="bt" href="#how">Let's go</a>
    </div>
    <div id="how">
        <h1>What do we do?</h1>
        <div class="info">
            <div class="idea">
                <div class="wrapfontawes">
                </div>
                <h3>Automate Patient Contacting</h3>
                <p>We automate notifying patients on the waitlist of earlier appointments, as well as of changes to their booking</p>
            </div>
            <div class="idea">
                <div class="wrapfontawes">
                </div>
                <h3>Provide Patient Insights</h3>
                <p>Provide insights into appointment data, letting you know where you can increase your efficiency</p>
            </div>
            <div class="idea">
                <div class="wrapfontawes">
                </div>
                <h3>Interoperate</h3>
                <p>Works with most major EHR systems, meaning you are not locked in to a single vendor.</p>
            </div>
        </div>
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
        font-size: 3em;
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
    
    #how {
        background: linear-gradient(var(--brand-purp-dark), var(--brand-purp-lighter));
        /* background-color: var(--brand-purp-dark); */
        width: calc(100vw - 4vw);
        padding-left: 2vw;
        padding-right: 2vw;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        color: white;
        padding-top: 5vh;
        padding-bottom: 5vh;

    }

    #how > h1 {
        font-size: 3em;
    }

    .wrapfontawes {
        color: white;
        font-size: 2em;
    }

    #how > .info {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-evenly;
        width: 100vw;
        /* height: 40vh; */
    }

    .info > .idea {
        border-radius: 20px;
        width: 25vw;
    }

    .idea > h3 {
        font-size: 2em;
        padding: 0;
        padding-top: 2vh;
        margin: 0;
        color: white;
        justify-self: baseline;
    }

    .idea > p {
        width: 75%;
    }




</style>
<script>
    import imgHome from "../assets/musculacao.jpg";
</script>

<section class="intro" style="background-image: url({imgHome});">
    <div class="intro__wrapper wrap">
        <h1>Você está pronto<br /> para o desafio?</h1>
        <p>
            A Academia Local está pronta para te ajudar a chegar mais longe e
            alcançar sua melhor performance.
        </p>
        <a class="btn" href="/sobre">Sobre</a>
    </div>
</section>

<style>
    .intro {
        position: relative;
        display: grid;
        align-content: center;
        justify-content: start;
        min-height: 360px;
        background-size: cover;
        background-position: center;
    }
    .intro::after {
        position: absolute;
        content: "";
        inset: 0;
        background-color: rgba(0, 0, 0, 0.55);
    }
    .intro__wrapper {
        z-index: 1;
        max-width: 450px;
    }
    .btn {
        margin-top: 24px;
    }
    p {
        font-size: calc(18 / 16 * 1rem);
        margin-top: 16px;
    }
</style>

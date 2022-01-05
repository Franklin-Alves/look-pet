<template>
    <div class="content-section">
        <section class="image-section">
            <img src="/img/adocao.jpg" alt="">
        </section>
        <aside class="section-container">
            <h3>Lorem, ipsum dolor sit amet.</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis ducimus alias veritatis placeat delectus eos et hic repellat earum! Animi libero deleniti suscipit quisquam. Incidunt distinctio explicabo quibusdam perspiciatis. Dignissimos?</p>
            <a href="#" class="link-type-1">Ver Filhotes</a>
        </aside>
    </div>
    
    <div class="content-section">
        <aside class="section-container">
            <h3>Lorem, ipsum dolor sit amet.</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis ducimus alias veritatis placeat delectus eos et hic repellat earum! Animi libero deleniti suscipit quisquam. Incidunt distinctio explicabo quibusdam perspiciatis. Dignissimos?</p>
            <a href="#" class="link-type-1">Agende agora</a>
        </aside>
        <section class="image-section">
            <img src="/img/banho.jpg" alt="">
        </section>
    </div>
</template>

<script>
export default {
    name: 'ContentSection'
}
</script>

<style scoped>
    .content-section {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 20px;
        margin: 150px 20px 0 20px;
        background-color: #FFD700;
        border-radius: 8px;
    }

    .content-section img {
        width: 700px;
        border-radius: 8px 0 0 8px;
    }

    .section-container {
        display: flex;
        justify-content: space-around;
        flex-direction: column;
        margin: 0 15px;
    }

    .section-container h3 {
        text-align: initial;
        font-size: 25px;
        font-weight: 900;
        color:#000080;
    }

    .section-container p {
        font-size: 16px;
        font-weight: 500;
        margin: 40px 0;
        color: #000080;
        text-align: justify;
    }

    .section-container a {
        color: #fff;
    }
</style>
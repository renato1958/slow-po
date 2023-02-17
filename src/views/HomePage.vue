<template>
    <div class="main-container">
        <header class="page-header">
            <h1 class="primary-title">Slow Po </h1><span class="secondary-title">Il portale del lungoticino</span>
        </header>
        <main class="main-content">
            <section class="image">
                <img src="/img/under_construction.png" alt="sito in costruzione">
            </section>
            <section class="message">
                <p class="message-intro">E, come dice il nostro webmaster:</p>
                <p class="message-body">"Importante è cominciare!"</p>
            </section>
        </main>
    </div>    
</template>

<style scoped>
.main-container {
    min-height: 100vh;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.page-header {
    height: 150px;
    display: flex;
    width: 100%;
    justify-content: center;
    align-items: center;
    background-color: var(--straw-color);
}

.primary-title {
    font-size: 3rem;
    color: #345678;
    font-weight: 800;
    text-shadow: 3px 1px 1px grey;
    margin-right: 10%
}

.secondary-title {
    font-size: 1.5rem;
    font-style: italic;
    color: #676767;
    font-weight: 700;
}

.image {
    width: 60%;
    margin: 100px auto;
}

.image img {
    max-inline-size: 100%;
    max-block-size: auto;
}

.message {
    width: 100%;
    text-align: center;
}

.message-intro {
    font-size: 1.2rem;
    font-weight: 800;
    margin-bottom: 10px
}

.message-body {
    font-size: 1.5rem;
    font-weight: 900;
}    
</style>
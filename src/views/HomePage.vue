<template>
    <div class="main-container">
        <header class="page-header">
            <h1 class="primary-title">Slow Po </h1>
            <span class="secondary-title">Il portale del lungoticino</span>
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
    display: flex;
    flex-direction: column;
    justify-content: stretch;
    align-items: center;
}

.main-content {
    flex: 1 1;
    width: 100%;
    display: flex;
    flex-flow: column;
    justify-content: space-evenly;
    align-items: center;
}

.page-header {
    height: 120px;
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    background-color: var(--straw-color);
}

.primary-title {
    font-size: 2rem;
    color: #345678;
    font-weight: 800;
    text-shadow: 3px 1px 1px grey;
    margin-left: 7%;
}

.secondary-title {
    font-size: 1.2rem;
    font-style: italic;
    color: #676767;
    font-weight: 700;
    margin-right: 7%;
}

.image {
    width: 75%;
    max-width: 960px;
}

.image img {
    max-inline-size: 100%;
    max-block-size: auto;
}

.message {
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
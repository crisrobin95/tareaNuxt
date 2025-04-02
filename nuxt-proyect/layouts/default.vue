<template>
    <div>
        <nav>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/catalog">Catálogo</NuxtLink></li>
            </ul>
        </nav>
        <main>
            <h2>Menú</h2>
            <slot></slot>
        </main>
        <footer>

        </footer>
    </div>
</template>

<style scoped>
    nav {
    background-color: #f0f0f0;
    padding: 10px;
    }

    nav ul {
    list-style: none;
    display: flex;
    }

    nav li {
    margin-right: 20px;
    }

    footer {
    background-color: #e0e0e0;
    padding: 10px;
    text-align: center;
    }
</style>
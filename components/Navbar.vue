<template>
    <div>
        <div class="menu-btn">
        <span class="menu-btn__burger"></span>
        </div>
        <nav class="nav">
                <ul class="menu-nav">
                    <li class="menu-nav__item active">
                        <NuxtLink to="/" class="menu-nav__link">Home</NuxtLink>
                    </li>
                    <li class="menu-nav__item active">
                        <NuxtLink to="/about" class="menu-nav__link">About me</NuxtLink>
                    </li>
                    <li class="menu-nav__item active">
                        <NuxtLink to="/projects" class="menu-nav__link">My projects</NuxtLink>
                    </li>
                    <li class="menu-nav__item active">
                        <NuxtLink to="/contact" class="menu-nav__link">Contact</NuxtLink>
                    </li>
                </ul>
        </nav>
    </div>    
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>

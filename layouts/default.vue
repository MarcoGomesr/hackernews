<template>
    <div>
        <header>
            <nav>
                <nuxt-link class="link underline-hover" to="/">Home</nuxt-link>
                <nuxt-link class="link underline-hover" to="/show">Show</nuxt-link>
                <nuxt-link class="link underline-hover" to="/new">New</nuxt-link>
                <nuxt-link class="link underline-hover" to="/ask">ask</nuxt-link>
                <nuxt-link class="link underline-hover" to="/jobs">jobs</nuxt-link>
            </nav>
        </header>
        <nuxt/>
    </div>
</template>

<style>
.nuxt-link-exact-active{
    text-decoration: underline;
    font-weight: bold; 
}
</style>

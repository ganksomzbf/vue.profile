<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/profile..png" alt="">
            </div>
            <div class="content">
                <h3>hi, i am {{name}}</h3>
                <span>{{motto}}</span>
                <p>{{content}}</p>
                <router-link to="/about" class="btn"> about me <i class="fas fa-user"></i> </router-link>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar },
    data() {
        return {
            name: 'Sasiwimon Masing',
            motto: 'Belive the Impossible is Possible.',
            content: 'More 5 Years Of Experienced Developer With Front-End And Back-End .NET Programming In The Information Technology And Service Industry. Skilled In HTML, CSS, Javascript, Angular, React, MVC, C# And ORACLE, SQL Database Tools. A Strong Engineering Professional With A Bachelor Of Engineering (BE) Focused On Computer Engineering From Bangkok University.',
        }
    }
}
</script>

<style>

</style>
<template>
    <footer class="py-5" id="footer-main">
        <div class="container">
            <div class="row align-items-center justify-content-xl-between">
                <div class="col-xl-6">
                <div class="copyright text-center text-xl-left text-muted">
                    &copy; 2020
                    <router-link :to="{name: 'accueil'}" class="font-weight-bold ml-1" target="_blank">
                        Ibudo
                    </router-link>
                </div>
                </div>
                <div class="col-lg-6">
                    <ul class="nav nav-footer justify-content-center justify-content-lg-end">
                    <li class="nav-item">
                        <router-link :to="{name: 'accueil'}" class="nav-link">
                            Accueil
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{name: 'about'}" class="nav-link">
                            A propos
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{name: 'blog'}" class="nav-link">
                            Blog
                        </router-link>
                    </li>
                    <!-- <li class="nav-item">
                        <a href="#" class="nav-link" target="_blank"></a>
                    </li>-->
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {

}
</script>
<style>

</style>

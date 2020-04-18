<template>
    <header class="header-global ">
        <base-nav class="navbar-main bg-success" transparent type="" effect="light" expand>


            <div class="row " slot="content-header" slot-scope="{closeMenu}">

                <div class="col-6 collapse-close ">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>
<img src="img\theme\cervax.jpg" width="100vw">

            <ul class="navbar-nav align-items-lg-center ml-lg-auto">

                <li class="nav-item">
                        <router-link slot="brand" class="navbar-brand mr-lg-5 text-default" to="/">
                        Accueil
                        </router-link>
                </li>
                <li class="nav-item">
                        <router-link slot="brand" class="navbar-brand mr-lg-5 text-default" to="/landing">
                        Blog
                        </router-link>
                </li>
                                
                <li class="nav-item">
                        <router-link slot="brand" class="navbar-brand mr-lg-5 text-default" to="/register">
                        Contact
                        </router-link>
                </li>

                <form class="form-inline my-2 my-lg-0">
                    <input class="form-control mr-sm-2" type="search" placeholder="Recherche" aria-label="Search">
                    <button class="btn btn-outline-default my-2 my-sm-0" type="submit">Recherche</button>
                </form>

            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>

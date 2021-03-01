<template>
    <b-container>
        <b-row>
            <div id="nav" class="w-100 p-0">

                <b-navbar toggleable="sm" type="light" variant="light">

                    <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

                    <b-navbar-brand>BootstrapVue</b-navbar-brand>

                    <b-collapse id="nav-text-collapse" is-nav>

                    <b-navbar-nav class="text-right ml-auto">
                        <b-nav-item><router-link to="/">Home</router-link></b-nav-item>
                        <b-nav-item><router-link to="/about">About</router-link></b-nav-item>
                        <b-nav-item><router-link to="/contact-us">Contact Us</router-link></b-nav-item>
                    </b-navbar-nav>
                    </b-collapse>
                    
                </b-navbar>

            </div>
        </b-row>
    </b-container>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>
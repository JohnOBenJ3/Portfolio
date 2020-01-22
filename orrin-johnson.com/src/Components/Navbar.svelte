<script>
    export let navlist = [];
</script>

<!-- <---------------------------------------------> 
<!-- <------ Markup for the Navbar Component ------> 
<!-- <---------------------------------------------> 

<section id="nav-bar">
    <nav class="navbar main-background-color navbar-expand-md navbar-dark">
        <img src="images/logo.png" alt="" class="logo">
        <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation" >
        <span class="navbar-toggler-icon"/>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                {#each navlist as list}
                    <li class="nav-item">
                        <a class="nav-link light-color" href="{list.url}">{list.label}</a>
                    </li>
                {/each}
            </ul>
        </div>
    </nav>
</section>

<!-- <----------------------------------------------------------> 
<!-- <---------------Style for Navbar Component-----------------> 
<!-- <----------------------------------------------------------> 

<style>
    #nav-bar {
        position: sticky;
        top: 0;
        z-index: 10;
    }

    .navbar {
        padding: 0 20px !important;
    }

    .navbar-nav li {
        padding: 0 0 0 20px;
        top: 10px;
    }

    .navbar-nav li a {
        font-weight: 600;
        text-transform: uppercase;
        float: right;
        text-align: left;
        top: 10px;
    }

    .logo {
        padding: 0 20px;
    }

</style>
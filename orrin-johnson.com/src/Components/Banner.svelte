<script>
    export let bannerData = {};
    const { HEADING } = bannerData;
</script>

<!-- <--------------------------------------------------------------->
<!-- <----------------Markup for Banner Component--------------------> 
<!-- <--------------------------------------------------------------->

<section class="main-background-color light-color" id="banner">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <h1>{HEADING}</h1>                
            </div>
        </div>
    </div>
</section>


<style>

    section {
        padding-top: 5%;
    }

    h1 {
        font-size: 70px;
        font-weight: 600;
        margin-top: 100px;
        text-transform: uppercase;
    }

</style>
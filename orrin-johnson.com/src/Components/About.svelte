<script>
    export let aboutData = {};
    const { HEADING, BODY } = aboutData;
</script>


<!-- <----------------------------------------------------->
<!-- <----------- Markup for About Component -------------->
<!-- <----------------------------------------------------->

<section id="about" class="section gray-background-color">
    <div class="container">
        <h2 class="heading"><em>{HEADING}</em></h2>
        <div class="row section-body">
            <div class="col-md-6">
                <h3 class="about-body">{BODY}</h3>
                <img src="logo-2.png" alt="">
            </div>
        </div>
    </div>
</section>

<!-- <------------------------------------------------------> 
<!-- <-----------------Style For About Component------------>
<!-- <------------------------------------------------------>


<style>

    .about-body {
        margin-top: 8%;
        margin-bottom: 20px;
        font-family: 'Times New Roman', Times, serif;
    }

    .heading {
        font-size: 60px;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        padding-top: 300px;
    }

    #about {
        font-size: 30px;
    }

    img {
        width: 60px;
        height: 60px;
    }

</style>


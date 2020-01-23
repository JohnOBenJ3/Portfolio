<script>
    export let projectData = {};
    const { HEADING } = projectData;
</script>


<!-- <-------------------------------------------------------->
<!-- <--------------Markup for Projects Component------------->
<!-- <-------------------------------------------------------->


<section id="projects" class="section secondary-background-color light-color">
    <div class="container text-center">
        <h2 class="title"><em>{HEADING}</em></h2>
        <ul class="projects">
        <figure>
            <li><img src="animal-allies.png" alt="" id="allies"></li>
            <figcaption class="allies">Website about animal shelters in Denver Colorado.
            This is a full stack application with the front-end written in the
            JavaScript Library React, and the API back-end is written in the Python
            framework Flask.
            </figcaption>
        </figure>
        <figure>
            <li><img src="blog.png" alt=""></li>
            <figcaption class="blog">Personal Blog Site written using the Django framework.</figcaption>
        </figure>
        <figure>
            <li><img src="brew-buddy.png" alt=""></li>
            <figcaption class="brew">Latest work in progress. The data comes from OpenBreweyDb and the 
                front end is receiving the data with Svelte.
            </figcaption>
        </figure>
        </ul>
    </div>
</section>



<!-- <-------------------------------------------------------->
<!-- <--------------Style for Projects Component-------------->
<!-- <-------------------------------------------------------->


<style>

    img {
        width: 1300px;
        height: 800px;
        padding-top: 40px;
    }


    li   {
        list-style-type: none;
        margin: 150px 0;
    }
        

    li img {
        margin-left: -140px;

    }
    
    .projects {
        columns: 1;
        line-height: 50px;
    }

    .title {
        padding-top: 280px;
        font-size: 80px;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

    }

    .allies {
        font-size: 20px;
        float: bottom;
        position: relative;
        bottom: 120px;
    }

    .blog {
        font-size: 20px;
        float: bottom;
        position: relative;
        bottom: 120px;
    }

    .brew {
        font-size: 20px;
        float: bottom;
        position: relative;
        bottom: 120px;
    }



</style>
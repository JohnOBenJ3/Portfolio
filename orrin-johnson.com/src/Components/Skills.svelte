<script>
    export let skillsData = {};
    const { HEADING } = skillsData;
</script>


<!-- <------------------------------------------------------->
<!-- <--------------Markup for Skills Component-------------->
<!-- <------------------------------------------------------->

<section id="skills" class="section secondary-background-color light-color">
    <div class="container text-center">
    <img src="logo-2.png" alt="">
        <h2 class="title"><em>{HEADING}</em></h2>
    </div>
    <div class="skill-icons">
        <ul class="column">
            <li><i class="devicon-javascript-plain colored" id="javascript"></i></li>
            <li><i class="devicon-html5-plain-wordmark" id="html"></i></li>
            <li><i class="devicon-nodejs-plain-wordmark colored" id="node"></i></li>
            <li><i class="devicon-python-plain-wordmark colored" id="python"></i></li>
            <li><i class="devicon-react-original-wordmark colored" id="react"></i></li>
            <li><i class="devicon-postgresql-plain-wordmark colored" id="postgres"></i></li>
            <li><i class="devicon-css3-plain-wordmark colored" id="css"></i></li>
            <li><i class="devicon-git-plain colored" id="git"></i></li>
            <li><i class="devicon-mongodb-plain-wordmark" id="mongo"></i></li>
            <li><i class="devicon-express-original-wordmark" id="express"></i></li>
            <li><i class="devicon-django-plain-wordmark" id="django"></i></li>
            <li><i class="devicon-bootstrap-plain-wordmark" id="bootstrap"></i></li>
            <li><i class="devicon-heroku-original-wordmark" id="heroku"></i></li>
        </ul>
    </div>
</section>

<!-- <------------------------------------------------------->
<!-- <--------------Style for Skills Component--------------->
<!-- <------------------------------------------------------->

<style>

    ul {
        columns: 4;
        line-height: 100px;
        padding-top: 20px;
    }

    li {
        list-style-type: none;
        padding-left: 70px;


    }

    img {
        width: 60px;
        height: 60px;
        float: top;
        position: relative;
        top: 150px;
    }


    .title {
        font-size: 50px;
        padding-top: 170px;
        font-family: monospace;

    }

    .skill-icons {
        padding-top: 60px;
    }

    #javascript {
        font-size: 120px;
        padding-left: 20px;


    }

    #html {
        font-size: 120px;
        padding-left: 20px;

    }

    #node {
        font-size: 150px;
        padding-left: 20px;
        position: relative;
        bottom: 40px;
    }

    #python {
        font-size: 120px;
        padding-left: 20px;
    }

    #react {
        font-size: 120px;
        padding-left: 20px;

    }

    #postgres {
        font-size: 120px;
        padding-left: 20px;
        padding-top: 20px;
    }

    #css {
        font-size: 120px;
        padding-left: 20px;
    }

    #git {
        font-size: 120px;
        padding-left: 20px;

    }

    #mongo {
        font-size: 120px;
        padding-left: 20px;

    }

    #express {
        font-size: 120px;
        padding-left: 20px;
    }

    #django {
        font-size: 120px;
        padding-left: 20px;
        float: bottom;
        position: relative;
        bottom: 60px;
    }

    #bootstrap {
        font-size: 120px;
        padding-left: 20px;
    }

    #heroku {
        font-size: 120px;
        padding-left: 20px;
    }

</style>
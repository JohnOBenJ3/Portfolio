<script>
    export let footerData = {};
    const { DESCRIPTION, CONTACT_DETAILS } = footerData;
    const { HEADING, MOBILE, EMAIL } = CONTACT_DETAILS;
</script>


<!-- <------------------------------------------------------>
<!-- <---------------Markup for Footer Component------------>
<!-- <------------------------------------------------------>

<section class="main-background-color light-color" id="contact">
    <div class="container">
        <div class="row section-body">
            <div class="col-md-4 footer-box">
                <p class="footer-head">{HEADING}</p>
                <p>
                    <i class="fas fa-phone"/>
                        {MOBILE}
                </p>
                <p>
                    <i class="fas fa-envelope"/>
                        {EMAIL}
                </p>
            </div>
                <p class="copyright"><span>&copy;</span> orrin-johnson.com 2020</p>
        </div>
    </div>
</section>


<!-- <----------------------------------------------------------->
<!-- <---------------Style For Footer Component------------------>
<!-- <----------------------------------------------------------->


<style>

    .copyright {
        float: top;
        position: relative;
        top: 30px;
    }

</style>
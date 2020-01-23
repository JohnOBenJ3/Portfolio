<script>
	import DATA from "./Data/data";
	import Navbar from "./Components/Navbar.svelte";
	import Banner from "./Components/Banner.svelte";
	import About from "./Components/About.svelte";
	import Skills from "./Components/Skills.svelte";
	import Projects from "./Components/Projects.svelte";
	import Social from "./Components/Social.svelte";
	import Footer from "./Components/Footer.svelte";

</script>

<Navbar navlist={DATA.NAVBAR_DATA} header={DATA.HEADER} />
<Banner bannerData={DATA.BANNER_DATA} />
<Projects projectData={DATA.PROJECT_DATA} />
<About aboutData={DATA.ABOUT_DATA} />
<Skills skillsData={DATA.SKILLS_DATA} />
<Social socialData={DATA.SOCIAL_DATA} />
<Footer footerData={DATA.FOOTER_DATA} />
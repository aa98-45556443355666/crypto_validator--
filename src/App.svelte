<script>
  import Navbar from "./components/Navbar/Navbar.svelte";
  import Banner from "./components/Banner/Banner.svelte";
  import About from "./components/About/About.svelte";
  import HowtoStart from "./components/HowtoStart/HowtoStart.svelte";
  import Footer from "./components/Footer/Footer.svelte";
  import DATA from "./data/data";
  console.log(DATA);
</script>



<!--Navbar-->
<Navbar navlists={DATA.NAVBAR_DATA} header={DATA.HEADER} />
<Banner bannerData={DATA.BANNER_DATA} />
<About aboutData={DATA.ABOUT_DATA} />
<HowtoStart startData={DATA.HOWTOSTART_DATA} />
<Footer footerData={DATA.FOOTER_DATA} />

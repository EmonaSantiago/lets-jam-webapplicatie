<script>
  import { assets } from "$app/paths";
  import "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/lets-jam-webapplicatie/src/styles/globalstyles.css";
  import Header from "../components/header.svelte";
  import HeroSection from "../components/hero-section.svelte";
  import Navigation from "../components/navigation.svelte";
  import Sessions from "../components/sessions.svelte";
  import SignUp from "../components/sign-up.svelte";
  import Upcoming from "../components/upcoming.svelte";
  import Footer from "../components/footer.svelte";
</script>

{assets}
<Header />
<HeroSection />
<Navigation />
<Sessions />
<SignUp />
<Upcoming />
<Footer />

<script>
  import { assets } from "$app/paths";
  import "./+page.svelte";
  import Header from "../lib/components/header.svelte";
  import HeroSection from "../lib/components/hero-section.svelte";
  import Navigation from "../lib/components/navigation.svelte";
  import Sessions from "../lib/components/sessions.svelte";
  import SignUp from "../lib/components/sign-up.svelte";
  import Upcoming from "../lib/components/upcoming.svelte";
  import Footer from "../lib/components/footer.svelte";
</script>

{assets}
<Header />
<HeroSection />
<Navigation />
<Sessions />
<SignUp />
<Upcoming />
<Footer />

<script lang="ts">
  import TopBanner from "$lib/components/TopBanner.svelte";
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Intro from "$lib/components/Intro.svelte";
  import Carousel from "$lib/components/Carousel.svelte";
  import ValueProp from "$lib/components/ValueProp.svelte";
  import ShowroomGrid from "$lib/components/ShowroomGrid.svelte";
  import LifeWithBackyard from "$lib/components/LifeWithBackyard.svelte";
  import ProductConfigurator from "$lib/components/ProductConfigurator.svelte";
  import PeekInside from "$lib/components/PeekInside.svelte";
  import Steps from "$lib/components/Steps.svelte";
  import Features from "$lib/components/Features.svelte";
  import Illustration from "$lib/components/Illustration.svelte";
  import Sustainability from "$lib/components/Sustainability.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
  <title>BuildIt AI - Turn Renovation Ideas into Reality with AI Visualization</title>
  <meta name="description" content="BuildIt AI turns renovation ideas into contractor-matched projects via AI visualization and marketplace bidding. Visualize your space, get competitive bids, and find trusted contractors." />
  <meta property="og:title" content="BuildIt AI - AI-Powered Renovation Platform" />
  <meta property="og:description" content="Transform your space with AI visualization and connect with verified contractors. Coming soon to iOS and Android." />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="BuildIt AI - Turn Renovation Ideas into Reality" />
  <meta name="twitter:description" content="AI-powered design visualization meets contractor marketplace. Join the waitlist today." />
</svelte:head>

<div class="font-sans antialiased text-gray-900 bg-white">
  <TopBanner />
  <Navbar />
  <main>
    <Hero />
    <Intro />
    <Carousel />
    <ValueProp />
    <ShowroomGrid />
    <LifeWithBackyard />
    <ProductConfigurator />
    <PeekInside />
    <Steps />
    <Features />
    <Illustration />
    <Sustainability />
  </main>
  <Footer />
</div>


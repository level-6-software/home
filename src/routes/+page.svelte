<script lang="ts">
	import GlowingBalls from "$lib/GlowingBalls.svelte";
    import Navbar from "$lib/Navbar.svelte";
	import GridFeature from "../lib/GridFeature.svelte";
    import Footer from "../lib/Footer.svelte";
    import Team from "../lib/Team.svelte";
	import Stats from "../lib/Stats.svelte";
	import Testimonial from "../lib/Testimonial.svelte";
	import Faq from "../lib/FAQ.svelte";

</script>

<div class="bg-white absolute w-full">
    <div class="z-0">
        <GlowingBalls />
    </div>

    <div class="absolute z-50 glass top-0 w-full">
        
        <Navbar />
    
        <div class="relative isolate pt-14">
       
        <div class="py-24 sm:py-32 lg:pb-40">
            <div class="mx-auto max-w-7xl px-6 lg:px-8">
            <div class="mx-auto max-w-2xl text-center">
                <h1 class="text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl">
                    E-Commerce that works for you.
                </h1>
                <p class="mt-6 text-lg leading-8 text-gray-600">We build the commerce platform. You run your store.</p>
                <div class="mt-10 flex items-center justify-center gap-x-6">
                <a href="#" class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Contact Us</a>
                <a href="#" class="text-sm font-semibold leading-6 text-gray-900">Learn more <span aria-hidden="true">→</span></a>
                </div>
            </div>
            <div class="mt-16 flow-root sm:mt-24">
                <div class="-m-2 rounded-xl bg-gray-900/5 p-2 ring-1 ring-inset ring-gray-900/10 lg:-m-4 lg:rounded-2xl lg:p-4">
                <img src="/admin-panel.png" alt="App screenshot" width="2432" height="1442" class="rounded-md shadow-2xl ring-1 ring-gray-900/10">
                </div>
            </div>
            </div>
        </div>
        
        </div>
    </div>


    <GridFeature />

    <Testimonial />

    <Faq />

    <Stats />

    <Team />

    <Footer />



</div>


<style>
.glass {
    /* From https://css.glass */
    background: rgba(255, 255, 255, 0.43);
    backdrop-filter: blur(12.8px);
    -webkit-backdrop-filter: blur(12.8px);
}

</style>
<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Zero friction",
			description: "Eliminating every technical barrier that stands between expertise and income, so professionals can focus on what they do best."
		},
		{
			title: "Expert empowerment",
			description: "Transforming displaced professionals into confident, monetized experts through AI-powered tools and instant payment integration."
		},
		{
			title: "Immediate value",
			description: "Delivering instant revenue generation from day one, because expertise should generate income immediately, not someday."
		}
	];
</script>

<SecondaryHero
	generating
	title="Solving world hunger"
	subtitle="one step at a time"
	imageSrc="https://www.unc.mn/image-placeholder.svg"
/>

<!-- Story Section -->
<Story
	generating
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Meet our founders."
	subtitle="Experienced professionals transforming expert monetization."
	stakeholders={[
		{
			name: "Kenny Rueter",
			position: "Co-founder",
			bio: "Kenny experienced the complexity of existing expert platforms firsthand. His drive to eliminate technical barriers for knowledge workers stems from witnessing countless experts struggle with monetization friction.",
			image: "/generated/image-professional-headshot-of-a-confident-bus.webp"
		},
		{
			name: "Jonathan Cronstedt",
			position: "Co-founder",
			bio: "Jonathan experienced the gap between expert knowledge and accessible web presence creation. His technical background combined with understanding creator economy pain points makes him ideal for building AI-powered expert tools.",
			image: "/generated/image-professional-headshot-of-a-tech-industry.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Transform your expertise into income"
	subtitle="Join the expert revolution"
	description="Stop wasting time on complex platforms that delay your success. PulsePage gets you from displaced professional to monetized expert in minutes, not months. Join thousands who've already transformed their expertise into thriving revenue streams."
/>

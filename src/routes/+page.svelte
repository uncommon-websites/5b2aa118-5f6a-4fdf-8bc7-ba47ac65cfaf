<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Turn your expertise into instant revenue"
	subtitle="Transform from displaced professional to monetized expert with AI-powered onboarding and instant payment integration. Start earning from your knowledge today."
	imageSrc="/generated/image-a-professional-consultant-stands-and-spe.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders" 
	logoUrls={[
		'https://cdn.brandfetch.io/masterclass.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/teachable.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/thinkific.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/skillshare.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="PulsePage transforms displaced tech professionals into monetized experts through AI-powered onboarding and instant payment integration. We eliminate the 40+ hours typically wasted building websites that fail to convert, giving you a credible online presence that generates revenue from day one.

Whether you're transitioning from corporate roles or expanding your consulting practice, our platform combines zero-friction setup with immediate monetization tools to capture your share of the $104B global professional services market."
/>

<Testimonials
	testimonials={[
		{
			name: "Miranda Chen",
			position: "Executive Leadership Coach",
			company: "Chen Consulting Group",
			quote:
				"PulsePage saved me 60+ hours of website development and generated $12K in revenue within my first month. The AI onboarding had my expert profile live in under 20 minutes, and the payment integration meant I could start monetizing immediately.",
			image: "/generated/image-a-professional-executive-coach-woman-wit.webp"
		},
		{
			name: "Marcus Rodriguez",
			position: "Business Strategy Consultant",
			company: "Strategic Solutions Co.",
			quote:
				"After being displaced from my corporate role, PulsePage eliminated the technical barriers that were keeping me from monetizing my expertise. I went from zero online presence to earning $8K monthly in consulting fees within 6 weeks.",
			image: "/generated/image-a-business-consultant-man-appearing-sati.webp"
		},
		{
			name: "Amara Williams",
			position: "Digital Marketing Strategist",
			company: "Williams Marketing Lab",
			quote:
				"The platform's instant payment integration and credible expert positioning helped me triple my consulting rates. Instead of wasting time building a website that doesn't convert, I focused on serving clients and grew my revenue to $15K monthly.",
			image: "/generated/image-a-marketing-strategist-woman-exuding-suc.webp"
		}
	]}
/>

<Features
	title="Transform expertise into revenue streams"
	subtitle="Skip the 40-hour website build and start monetizing your knowledge immediately with AI-powered automation"
	features={[
		{
			title: "AI-powered expert onboarding",
			description: "Transform from displaced professional to monetized expert in under 10 minutes with intelligent profile creation and instant credibility building.",
			imageSrc: "/generated/image-a-confident-professional-consultant-givi.webp"
		},
		{
			title: "Instant payment integration",
			description: "Start earning from your first consultation with seamless payment processing and automated invoicing.",
			imageSrc: "/generated/image-a-freelance-coach-working-at-a-tidy-desk.webp"
		},
		{
			title: "Zero-friction client booking",
			description: "Convert prospects into paying clients with smart scheduling that eliminates back-and-forth communication.",
			imageSrc: "/generated/image-an-expert-advisor-meeting-with-a-client-.webp"
		},
		{
			title: "Professional credibility builder",
			description: "Establish instant authority with AI-generated case studies and testimonials that showcase your expertise authentically.",
			imageSrc: "/generated/image-an-expert-mentor-conducting-a-coaching-s.webp"
		},
		{
			title: "Revenue optimization insights",
			description: "Maximize earning potential with data-driven recommendations on pricing, services, and client acquisition strategies.",
			imageSrc: "/generated/image-a-professional-consultant-reviewing-prin.webp"
		},
		{
			title: "Multi-channel content automation",
			description: "Scale your expertise across platforms with AI-generated content that maintains your unique voice and builds thought leadership.",
			imageSrc: "/generated/image-a-tech-professional-brainstorming-conten.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />

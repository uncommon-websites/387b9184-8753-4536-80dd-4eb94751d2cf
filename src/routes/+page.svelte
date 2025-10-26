<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconShield from "~icons/lucide/shield";
	import IconKey from "~icons/lucide/key";
	import IconLock from "~icons/lucide/lock";
	import IconUsers from "~icons/lucide/users";
	import IconHeadset from "~icons/lucide/headset";
	import IconTrendingUp from "~icons/lucide/trending-up";
</script>

<CenteredTextOnlyHero
	title="Complete control of your Bitcoin"
	subtitle="Multi-key vault technology that eliminates exchange risk and protects your wealth from theft and loss."
	imageSrc="/generated/image-a-minimalist-scene-featuring-a-group-of-.webp"
/>
<LogoScroller
	label="Trusted by Bitcoin leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/kraken.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/microstrategy.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/block.xyz/w/400/h/400/logo',
		'https://cdn.brandfetch.io/coinbase.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Casa provides multi-key vault technology for Bitcoin holders with significant wealth who need secure self-custody without the risk of exchange hacks or losing access. Our premium service secures billions in digital assets globally, offering the control of self-custody with the confidence of Swiss banking. From personalized onboarding to inheritance planning, we deliver complete protection for your life-changing wealth."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Bitcoin Investor",
			company: "Early Adopter Since 2015",
			quote:
				"After the exchange hacks in 2022, I moved $4.2M to Casa's multi-key vault. Setup took 90 minutes with their team, versus weeks trying to figure out self-custody alone. The peace of mind knowing my wealth is protected from both hackers and my own mistakes is invaluable.",
			image: "/generated/image-professional-headshot-of-an-asian-male-b.webp"
		},
		{
			name: "Elena Ramirez",
			position: "Family Office Manager",
			company: "Ramirez Holdings",
			quote:
				"Casa's inheritance planning saved us from a potential disaster. Our attorney estimated we avoided $800K in estate complications by properly structuring multi-generational access. The platform makes something incredibly complex feel simple and secure.",
			image: "/generated/image-professional-headshot-of-a-hispanic-woma.webp"
		},
		{
			name: "Raj Patel",
			position: "Technology Entrepreneur",
			company: "Blockchain Ventures",
			quote:
				"I'm technical enough to run my own node, but Casa's architecture is brilliant. Their multi-key vault eliminated single points of failure that kept me up at night. The premium support responds in minutes, not hours. Worth every penny for securing $2.8M.",
			image: "/generated/image-professional-headshot-of-a-south-asian-m.webp"
		}
	]}
/>

<Features
	title="Built for security and peace of mind"
	subtitle="Our multi-key vault technology delivers the security Bitcoin investors need to protect life-changing wealth."
	features={[
		{
			title: "Multi-key vault security",
			description:
				"Advanced multi-key architecture protects your Bitcoin from hacks, theft, and single points of failure with distributed key management.",
			icon: IconShield
		},
		{
			title: "Complete self-custody",
			description:
				"Take full control of your Bitcoin without intermediaries or exchanges, ensuring you always maintain sovereignty over your wealth.",
			icon: IconKey
		},
		{
			title: "Protection from loss",
			description:
				"Our vault technology safeguards against accidental loss and theft while maintaining secure access for authorized users.",
			icon: IconLock
		},
		{
			title: "Inheritance planning",
			description:
				"Integrated tools for secure generational wealth transfer ensure your Bitcoin reaches your heirs according to your wishes.",
			icon: IconUsers
		},
		{
			title: "White-glove service",
			description:
				"Personalized onboarding and dedicated support provide a premium experience comparable to Swiss private banking.",
			icon: IconHeadset
		},
		{
			title: "Proven at scale",
			description:
				"Trusted by clients worldwide to secure billions in digital assets with a 4.9 App Store rating and years of proven security.",
			icon: IconTrendingUp
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Take control before someone else does"
	subtitle="Secure your Bitcoin today—before risk becomes regret"
	description="Your Bitcoin is only safe if you control it. Casa makes self-custody simple, secure, and stress-free—no technical expertise required. Our multi-key vaults eliminate single points of failure, and our expert team guides you every step of the way."
	imageSrc="/generated/image-a-confident-professional-sits-at-a-moder.webp"
	callsToAction={[
		{
			href: "/",
			label: "Schedule free consultation",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>

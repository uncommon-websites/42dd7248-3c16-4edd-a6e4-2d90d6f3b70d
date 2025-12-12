<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-serif font-normal mb-16">Pricing</h2>

		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			<!-- Enterprise -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Enterprise</h3>
				<p class="text-gray-400 text-sm mb-6">Custom pricing</p>
				<button class="bg-white text-black px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-gray-200 transition-colors">
					Request demo
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EVERYTHING IN PROFESSIONAL +</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited security team members and cloud environments</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>All pre-built connectors in marketplace</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>SAML SSO, SCIM provisioning, and audit logs</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom AI model training on your data</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Advanced analytics and reporting dashboard</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Dedicated security architect and 24/7 support with SLA</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-[#a3e635] flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>API access for custom integrations</span>
					</li>
				</ul>
			</div>

			<!-- Professional -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Professional</h3>
				<p class="text-orange-500 text-sm mb-6">$99 / user per month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Start trial
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EVERYTHING IN STARTER +</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited visual documentation captures</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 50 security team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Popular security integrations: AWS, Azure, GCP, Splunk, Datadog</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Advanced AI threat detection models</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>SOC 2 Type 2 and compliance certifications</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited cloud environments monitored</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-orange-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Priority email and chat support</span>
					</li>
				</ul>
			</div>

			<!-- Starter -->
			<div>
				<h3 class="text-xl font-bold mb-2">Starter</h3>
				<p class="text-pink-500 text-sm mb-6">$49 / user per month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Start trial
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">IDEAL FOR SMALL TEAMS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>100 visual documentation captures per month</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 10 security team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>AI-powered tribal knowledge capture</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Basic cloud integrations: AWS, Azure, or GCP</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Slack and Microsoft Teams integration</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Monitor up to 3 cloud environments</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Email support</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>

<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-normal mb-8">Flexible engagement models</h2>
		<p class="text-gray-400 text-lg max-w-2xl mb-16">
			From pilot projects to enterprise-wide transformation, we tailor our approach to your needs and budget.
		</p>

		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			<!-- Enterprise -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Enterprise Transformation</h3>
				<p class="text-gray-400 text-sm mb-6">Custom pricing</p>
				<button class="bg-primary-600 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-primary-700 transition-colors">
					Schedule consultation
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">Comprehensive Solution</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Full four-phase implementation framework</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Celonis platform configuration and deployment</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Multiple process areas (P2P, O2C, Supply Chain)</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>AI-enhanced predictive analytics</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Dedicated implementation team</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Ongoing training and enablement</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Continuous monitoring and optimization</span>
					</li>
				</ul>
			</div>

			<!-- Department -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Department Focus</h3>
				<p class="text-primary-400 text-sm mb-6">Starting at $50K</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Request quote
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">Single Process Area</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Discovery and proposition phases</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Single process area (e.g., Procurement or O2C)</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Celonis platform setup and configuration</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Process mining and bottleneck analysis</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom dashboards and KPIs</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>User training and documentation</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>3 months post-implementation support</span>
					</li>
				</ul>
			</div>

			<!-- Pilot -->
			<div>
				<h3 class="text-xl font-bold mb-2">Pilot Project</h3>
				<p class="text-primary-400 text-sm mb-6">Starting at $25K</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Get started
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">Proof of Value</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>6-8 week engagement</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Limited process scope (1-2 workflows)</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Process discovery and analysis</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Identify quick wins and opportunities</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>ROI projection and business case</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Executive presentation and roadmap</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Ideal for testing process mining value</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>

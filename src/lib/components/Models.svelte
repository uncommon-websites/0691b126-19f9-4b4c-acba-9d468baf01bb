<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
            <!-- Text Content -->
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-6 leading-tight">
					From data to insights<br />
					to measurable impact
				</h2>
				<p class="text-gray-400 text-lg max-w-md mb-8">
					Our Enterprise Intelligence framework combines process mining with AI-driven analytics to deliver actionable insights that drive real business outcomes.
				</p>
				<div class="space-y-4">
					<div class="flex items-start gap-3">
						<div class="w-6 h-6 rounded-full bg-primary-500/20 border border-primary-500/40 flex items-center justify-center text-primary-400 text-xs font-bold mt-0.5">✓</div>
						<div>
							<div class="text-white font-medium">Data-Driven Decision Making</div>
							<div class="text-sm text-gray-400">Move beyond intuition with complete process visibility</div>
						</div>
					</div>
					<div class="flex items-start gap-3">
						<div class="w-6 h-6 rounded-full bg-primary-500/20 border border-primary-500/40 flex items-center justify-center text-primary-400 text-xs font-bold mt-0.5">✓</div>
						<div>
							<div class="text-white font-medium">Documented ROI Benchmarks</div>
							<div class="text-sm text-gray-400">Proven process savings across industries</div>
						</div>
					</div>
					<div class="flex items-start gap-3">
						<div class="w-6 h-6 rounded-full bg-primary-500/20 border border-primary-500/40 flex items-center justify-center text-primary-400 text-xs font-bold mt-0.5">✓</div>
						<div>
							<div class="text-white font-medium">Continuous Improvement</div>
							<div class="text-sm text-gray-400">Ongoing monitoring and optimization</div>
						</div>
					</div>
				</div>
			</div>

            <!-- Process Flow Mockup -->
			<div class="bg-[#0f0f0f] rounded-xl p-12 border border-white/5 relative overflow-hidden h-[600px] flex items-center justify-center">
                <div class="w-full h-full relative">
					<!-- Vertical process flow -->
					<div class="absolute inset-0 flex flex-col justify-around items-center py-8">
						<div class="w-full max-w-xs">
							<div class="bg-[#1a1a1a] border border-primary-500/40 rounded-lg p-4 relative">
								<div class="absolute -left-3 top-1/2 -translate-y-1/2 w-6 h-6 rounded-full bg-primary-500 flex items-center justify-center text-white text-xs font-bold">1</div>
								<div class="text-sm font-medium text-white mb-1">Process Discovery</div>
								<div class="text-xs text-gray-400">Map actual workflows from system data</div>
							</div>
						</div>
						
						<div class="w-px h-12 bg-primary-500/40"></div>
						
						<div class="w-full max-w-xs">
							<div class="bg-[#1a1a1a] border border-primary-500/40 rounded-lg p-4 relative">
								<div class="absolute -left-3 top-1/2 -translate-y-1/2 w-6 h-6 rounded-full bg-primary-500 flex items-center justify-center text-white text-xs font-bold">2</div>
								<div class="text-sm font-medium text-white mb-1">AI Analysis</div>
								<div class="text-xs text-gray-400">Identify inefficiencies and predict risks</div>
							</div>
						</div>
						
						<div class="w-px h-12 bg-primary-500/40"></div>
						
						<div class="w-full max-w-xs">
							<div class="bg-[#1a1a1a] border border-primary-500/40 rounded-lg p-4 relative">
								<div class="absolute -left-3 top-1/2 -translate-y-1/2 w-6 h-6 rounded-full bg-primary-500 flex items-center justify-center text-white text-xs font-bold">3</div>
								<div class="text-sm font-medium text-white mb-1">Optimization</div>
								<div class="text-xs text-gray-400">Implement improvements and track impact</div>
							</div>
						</div>
						
						<div class="w-px h-12 bg-primary-500/40"></div>
						
						<div class="w-full max-w-xs">
							<div class="bg-[#1a1a1a] border border-green-500/40 rounded-lg p-4 relative">
								<div class="absolute -left-3 top-1/2 -translate-y-1/2 w-6 h-6 rounded-full bg-green-500 flex items-center justify-center text-white text-xs font-bold">✓</div>
								<div class="text-sm font-medium text-white mb-1">Measurable Results</div>
								<div class="text-xs text-gray-400">Documented savings and efficiency gains</div>
							</div>
						</div>
					</div>
                </div>
			</div>
		</div>
	</div>
</section>

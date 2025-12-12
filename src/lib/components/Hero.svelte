<script lang="ts">
	import { onMount } from 'svelte';
</script>

<section class="relative pt-32 pb-20 overflow-hidden bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="max-w-4xl">
			<h1 class="text-6xl md:text-7xl lg:text-[5.5rem] leading-[1.1] font-normal tracking-tight mb-8">
				Surface <span class="italic font-light">hidden inefficiencies.</span><br />
				Predict operational risks.
			</h1>

			<p class="text-xl text-gray-400 max-w-2xl mb-10 leading-relaxed font-light font-sans">
				AI-enhanced process mining that transforms operational data into strategic advantage. Built on the Celonis platform.
			</p>

			<div class="flex flex-wrap gap-4 mb-20">
				<button class="bg-primary-600 hover:bg-primary-700 text-white px-8 py-4 rounded-full font-medium transition-colors text-base">
					Schedule consultation
				</button>
				<button class="bg-white/10 hover:bg-white/20 border border-white/10 text-white px-8 py-4 rounded-full font-medium transition-colors text-base">
					View case studies
				</button>
			</div>
		</div>
	</div>

	<!-- Hero Image Container with Perspective -->
	<div class="relative w-full max-w-[1400px] mx-auto px-6 perspective-container">
		<div class="relative transform-3d hero-image-container origin-top opacity-90 hover:opacity-100 transition-opacity duration-700">
			<!-- Process Mining Dashboard Mockup -->
			<div class="rounded-xl overflow-hidden border border-white/10 shadow-2xl bg-[#0a0a0a] aspect-[16/10] relative">
				<!-- Top bar -->
				<div class="h-10 bg-[#111] border-b border-white/5 flex items-center px-4 gap-2">
                    <div class="flex gap-2">
                        <div class="w-3 h-3 rounded-full bg-red-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500/20"></div>
                    </div>
                    <div class="mx-auto w-1/3 h-6 bg-white/5 rounded-md text-[10px] flex items-center justify-center text-gray-500 font-mono">
                        celx.digital/process-intelligence
                    </div>
				</div>
				<!-- Content Mockup -->
				<div class="flex h-full">
                    <!-- Sidebar -->
                    <div class="w-64 border-r border-white/5 bg-[#0f0f0f] p-4 hidden md:block">
                        <div class="space-y-4">
                            <div class="h-8 w-full bg-primary-500/10 rounded border border-primary-500/20 flex items-center px-3 text-[10px] text-primary-300">Process Overview</div>
                            <div class="space-y-2 mt-8">
                                <div class="h-4 w-3/4 bg-white/5 rounded opacity-50"></div>
                                <div class="h-4 w-1/2 bg-white/5 rounded opacity-50"></div>
                                <div class="h-4 w-2/3 bg-white/5 rounded opacity-50"></div>
                            </div>
                        </div>
                    </div>
                    <!-- Main Content -->
                    <div class="flex-1 p-8 bg-[#0a0a0a]">
                        <div class="flex justify-between items-end mb-8">
                            <div>
                                <div class="h-10 w-64 bg-white/10 rounded mb-2 flex items-center px-4 text-xs text-white">Process Efficiency Dashboard</div>
                                <div class="h-4 w-48 bg-white/5 rounded"></div>
                            </div>
                            <div class="h-10 w-32 bg-primary-500/20 rounded border border-primary-500/30"></div>
                        </div>
                        
                        <div class="grid grid-cols-3 gap-6 mb-8">
                            <div class="bg-[#111] p-4 rounded-lg border border-white/5 h-32 flex flex-col justify-between">
                                <div class="text-[10px] text-gray-400">Hidden Inefficiencies</div>
                                <div class="text-2xl text-primary-400 font-bold">$2.4M</div>
                            </div>
                            <div class="bg-[#111] p-4 rounded-lg border border-white/5 h-32 flex flex-col justify-between">
                                <div class="text-[10px] text-gray-400">Process Bottlenecks</div>
                                <div class="text-2xl text-yellow-400 font-bold">14</div>
                            </div>
                            <div class="bg-[#111] p-4 rounded-lg border border-white/5 h-32 flex flex-col justify-between">
                                <div class="text-[10px] text-gray-400">Cycle Time Reduction</div>
                                <div class="text-2xl text-green-400 font-bold">38%</div>
                            </div>
                        </div>

                        <div class="bg-[#111] rounded-lg border border-white/5 h-64 w-full p-6 relative overflow-hidden">
                             <!-- Process Flow Visualization -->
                             <div class="absolute bottom-0 left-0 right-0 h-32 bg-gradient-to-t from-primary-500/10 to-transparent"></div>
                             <svg class="w-full h-full text-primary-500/50" viewBox="0 0 100 50" preserveAspectRatio="none">
                                 <path d="M0 50 L10 40 L20 45 L30 30 L40 35 L50 20 L60 25 L70 15 L80 20 L90 10 L100 5 V50 H0 Z" fill="currentColor" />
                             </svg>
                        </div>
                    </div>
                </div>

				<!-- Gradient Overlay -->
				<div class="absolute inset-0 bg-gradient-to-t from-black/40 via-transparent to-transparent pointer-events-none"></div>
			</div>
		</div>
	</div>
    
    <!-- Client Logos -->
    <div class="max-w-[1400px] mx-auto px-6 mt-20">
        <p class="text-center text-gray-500 text-sm mb-8 uppercase tracking-wider">Trusted by process-driven enterprises</p>
        <div class="flex flex-wrap justify-center md:justify-between items-center gap-8 opacity-50 grayscale hover:grayscale-0 transition-all duration-500">
            <!-- Manufacturing and Enterprise Client Placeholders -->
            <span class="text-xl font-bold font-sans tracking-tight">SIEMENS</span>
            <span class="text-xl font-bold font-sans">BMW Group</span>
            <span class="text-xl font-bold font-sans tracking-widest">ABB</span>
            <span class="text-xl font-bold font-sans">Bosch</span>
            <span class="text-xl font-bold font-sans">Schneider Electric</span>
            <span class="text-xl font-bold font-sans">Honeywell</span>
        </div>
    </div>
</section>

<style>
	.perspective-container {
		perspective: 2000px;
	}
	.transform-3d {
		transform: rotateX(20deg) scale(0.9);
        transform-style: preserve-3d;
	}
</style>

<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-6">
				Enterprise Intelligence<br />
				powered by process mining
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				Transform operational data into strategic advantage with AI-driven insights built on the Celonis platform.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: Discover -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Discover</h3>
					<p class="text-gray-400 text-sm">Map your actual processes from system data</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex items-center justify-center">
                         <!-- Process flow visualization -->
                         <div class="w-full h-full border border-white/5 rounded-lg bg-[#0a0a0a] p-6 relative">
                             <div class="absolute top-8 left-8 text-gray-500 text-xs font-mono">
                                 Process Discovery<br/>
                                 Order-to-Cash Flow
                             </div>
                             <!-- Process nodes -->
                             <div class="absolute top-1/3 left-12 w-16 h-16 rounded-lg bg-primary-500/20 border border-primary-500/40 flex items-center justify-center text-xs text-primary-300">Start</div>
                             <div class="absolute top-1/3 left-36 w-20 h-px bg-primary-500/40"></div>
                             <div class="absolute top-1/3 left-60 w-16 h-16 rounded-lg bg-primary-500/20 border border-primary-500/40"></div>
                             <div class="absolute top-1/3 left-80 w-20 h-px bg-primary-500/40"></div>
                             <div class="absolute top-1/3 right-12 w-16 h-16 rounded-lg bg-primary-500/20 border border-primary-500/40 flex items-center justify-center text-xs text-primary-300">End</div>
                         </div>
                    </div>
                </div>
			</div>

			<!-- Card 2: Analyze -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Analyze</h3>
					<p class="text-gray-400 text-sm">Identify bottlenecks and inefficiencies with AI</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <!-- Top stats row -->
                    <div class="flex gap-4 mb-6">
                        <div class="bg-primary-500/10 p-4 rounded w-1/3 border border-primary-500/20">
                            <div class="text-xs text-primary-300 mb-1">Inefficiencies</div>
                            <div class="text-xl font-bold text-primary-400">$2.4M</div>
                        </div>
                         <div class="bg-yellow-500/10 p-4 rounded w-1/3 border border-yellow-500/20">
                            <div class="text-xs text-yellow-300 mb-1">Bottlenecks</div>
                            <div class="text-xl font-bold text-yellow-400">14</div>
                        </div>
                         <div class="bg-green-500/10 p-4 rounded w-1/3 border border-green-500/20">
                            <div class="text-xs text-green-300 mb-1">Opportunities</div>
                            <div class="text-xl font-bold text-green-400">27</div>
                        </div>
                    </div>
                    
                    <!-- Chart -->
                    <div class="flex-1 w-full relative mt-4">
                         <svg class="w-full h-full overflow-visible" viewBox="0 0 100 50" preserveAspectRatio="none">
                             <!-- Grid lines -->
                             <line x1="0" y1="10" x2="100" y2="10" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="25" x2="100" y2="25" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="40" x2="100" y2="40" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             
                             <!-- Lines -->
                             <path d="M0 45 C 20 40, 40 30, 60 25 S 80 15, 100 5" fill="none" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" />
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30" fill="none" stroke="#10b981" stroke-width="2" />
                             
                             <!-- Area under curve -->
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30 V 50 H 0 Z" fill="#10b981" fill-opacity="0.1" />
                         </svg>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Predict -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Predict</h3>
					<p class="text-gray-400 text-sm">AI-driven forecasting of operational risks</p>
				</div>
                
                 <!-- Mockup Content - Risk Dashboard -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4 text-[10px] leading-relaxed text-gray-400 shadow-inner">
                    <div class="flex gap-1.5 mb-4 border-b border-white/5 pb-2">
                        <div class="text-xs text-gray-500">Risk Prediction Dashboard</div>
                    </div>
                    <div class="space-y-3">
                        <div class="bg-red-500/10 border border-red-500/30 rounded p-3">
                            <div class="text-red-400 font-semibold mb-1">High Risk</div>
                            <div class="text-gray-400">Supply chain delay predicted in 14 days</div>
                        </div>
                        <div class="bg-yellow-500/10 border border-yellow-500/30 rounded p-3">
                            <div class="text-yellow-400 font-semibold mb-1">Medium Risk</div>
                            <div class="text-gray-400">Invoice processing bottleneck forming</div>
                        </div>
                        <div class="bg-green-500/10 border border-green-500/30 rounded p-3">
                            <div class="text-green-400 font-semibold mb-1">Opportunity</div>
                            <div class="text-gray-400">Process automation potential identified</div>
                        </div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Optimize -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Optimize</h3>
					<p class="text-gray-400 text-sm">Implement improvements and track impact</p>
				</div>
                
                 <!-- Mockup Content - Action Card -->
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-xl p-5 w-full shadow-2xl relative">
                        <!-- Glow effect -->
                        <div class="absolute -inset-1 bg-gradient-to-r from-primary-500/20 to-green-500/20 blur opacity-50"></div>
                        
                        <div class="relative bg-[#1a1a1a] rounded-xl">
                            <div class="flex items-center gap-3 mb-4">
                                <div class="w-8 h-8 rounded bg-primary-500/20 flex items-center justify-center shrink-0 border border-primary-500/40">
                                    <div class="w-3 h-3 bg-primary-400 rounded-full"></div>
                                </div>
                                <div>
                                    <div class="font-medium text-xs text-white">Process Improvement Initiative</div>
                                    <div class="text-[10px] text-gray-500">Procurement cycle optimization</div>
                                </div>
                            </div>
                            <div class="h-1.5 w-full bg-white/10 rounded-full overflow-hidden">
                                <div class="h-full bg-primary-500 w-2/3"></div>
                            </div>
                            <div class="mt-3 text-[10px] text-gray-400">67% complete • Est. savings: $840K</div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Monitor -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Monitor</h3>
					<p class="text-gray-400 text-sm">Continuous improvement and real-time alerts</p>
				</div>
                
                 <!-- Mockup Content - Monitoring Dashboard -->
                <div class="flex-1 relative flex flex-col gap-4">
                    <div class="bg-[#1a1a1a] rounded-lg p-4 text-xs text-gray-300 border border-white/5">
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-gray-500">Process Health Score</span>
                            <span class="text-green-400 font-bold">92/100</span>
                        </div>
                        <div class="h-2 w-full bg-white/10 rounded-full overflow-hidden">
                            <div class="h-full bg-green-500 w-[92%]"></div>
                        </div>
                    </div>
                    
                    <div class="flex-1 bg-gradient-to-br from-[#1a1a1a] to-black border border-white/10 rounded-lg overflow-hidden flex flex-col p-4">
                         <div class="text-[10px] text-gray-500 mb-3">Live Process Metrics</div>
                         <div class="space-y-2 flex-1">
                             <div class="flex justify-between text-xs">
                                 <span class="text-gray-400">Avg. Cycle Time</span>
                                 <span class="text-white">4.2 days</span>
                             </div>
                             <div class="flex justify-between text-xs">
                                 <span class="text-gray-400">Active Cases</span>
                                 <span class="text-white">1,247</span>
                             </div>
                             <div class="flex justify-between text-xs">
                                 <span class="text-gray-400">Efficiency Rate</span>
                                 <span class="text-primary-400">+12%</span>
                             </div>
                         </div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>

<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-12 leading-tight">
					Built for process-heavy<br />
					enterprises
				</h2>

				<div class="space-y-6">
					<div class="flex items-center gap-3 text-primary-400 font-medium">
						<div class="w-2 h-2 bg-primary-400 rounded-sm"></div>
						Manufacturing
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8">
						Optimize production workflows, reduce cycle times, and eliminate bottlenecks across your manufacturing operations with real-time process intelligence.
					</p>

					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Supply Chain & Logistics
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Finance Operations
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Procurement
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Order-to-Cash
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						General Operations
					</div>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative bg-gradient-to-br from-[#0f0f0f] to-black border border-white/5">
                     <!-- Process Mining Visualization -->
                     <div class="absolute inset-0 flex items-center justify-center p-12">
                         <div class="w-full h-full relative">
                             <!-- Process nodes connected -->
                             <div class="absolute top-1/4 left-1/4 w-20 h-20 rounded-lg bg-primary-500/20 border-2 border-primary-500/40 flex items-center justify-center">
                                 <div class="text-xs text-primary-300 font-mono">Start</div>
                             </div>
                             <div class="absolute top-1/4 left-1/2 w-20 h-20 rounded-lg bg-primary-500/20 border-2 border-primary-500/40"></div>
                             <div class="absolute top-1/2 right-1/4 w-20 h-20 rounded-lg bg-yellow-500/20 border-2 border-yellow-500/40 flex items-center justify-center">
                                 <div class="text-xs text-yellow-300 font-mono">Alert</div>
                             </div>
                             <div class="absolute bottom-1/4 left-1/3 w-20 h-20 rounded-lg bg-primary-500/20 border-2 border-primary-500/40 flex items-center justify-center">
                                 <div class="text-xs text-primary-300 font-mono">End</div>
                             </div>
                             
                             <!-- Connection lines -->
                             <svg class="absolute inset-0 w-full h-full" style="pointer-events: none;">
                                 <line x1="35%" y1="30%" x2="55%" y2="30%" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" opacity="0.4" />
                                 <line x1="60%" y1="35%" x2="75%" y2="55%" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" opacity="0.4" />
                                 <line x1="70%" y1="60%" x2="50%" y2="75%" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" opacity="0.4" />
                             </svg>
                         </div>
                     </div>
                     
                     <!-- Stats Overlay -->
                     <div class="absolute bottom-8 left-8 right-8 bg-[#0a0a0a]/90 backdrop-blur-sm rounded-xl p-4 border border-white/10 shadow-2xl">
                         <div class="grid grid-cols-3 gap-4 text-center">
                             <div>
                                 <div class="text-2xl font-bold text-primary-400">$2.4M</div>
                                 <div class="text-[10px] text-gray-500 mt-1">Savings Found</div>
                             </div>
                             <div>
                                 <div class="text-2xl font-bold text-yellow-400">14</div>
                                 <div class="text-[10px] text-gray-500 mt-1">Bottlenecks</div>
                             </div>
                             <div>
                                 <div class="text-2xl font-bold text-green-400">45%</div>
                                 <div class="text-[10px] text-gray-500 mt-1">Faster</div>
                             </div>
                         </div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>

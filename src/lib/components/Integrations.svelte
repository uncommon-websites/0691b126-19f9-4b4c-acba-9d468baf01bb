<script lang="ts">
    const integrations = [
        { name: 'SAP', color: 'bg-blue-600' },
        { name: 'Oracle', color: 'bg-red-600' },
        { name: 'Salesforce', color: 'bg-blue-400' },
        { name: 'Microsoft Dynamics', color: 'bg-blue-500' },
        { name: 'Workday', color: 'bg-blue-700' },
        { name: 'ServiceNow', color: 'bg-green-700' },
        { name: 'SAP S/4HANA', color: 'bg-blue-600' },
        { name: 'Ariba', color: 'bg-orange-500' },
        { name: 'Coupa', color: 'bg-red-500' },
        { name: 'NetSuite', color: 'bg-blue-800' },
        { name: 'JD Edwards', color: 'bg-red-700' },
        { name: 'Infor', color: 'bg-orange-600' },
        { name: 'IFS', color: 'bg-blue-500' },
        { name: 'Epicor', color: 'bg-green-600' },
        { name: 'Sage', color: 'bg-green-700' },
        { name: 'Concur', color: 'bg-blue-400' }
    ];

    const capabilities = [
        'Process Discovery', 'Bottleneck Analysis', 'Conformance Checking', 'Root Cause Analysis', 
        'Predictive Analytics', 'Real-time Monitoring', 'KPI Dashboards', 'Variant Analysis', 
        'Process Simulation', 'Automation Potential', 'Benchmark Comparison', 'Custom Reports'
    ];
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6 text-center">
		<h2 class="text-4xl md:text-5xl lg:text-6xl font-normal mb-6">
			Built on Celonis.<br />
			Connected to your systems.
		</h2>
		<p class="text-gray-400 text-lg max-w-2xl mx-auto mb-20">
			Seamlessly integrate with your ERP, CRM, and enterprise systems to unlock complete process visibility.
		</p>

		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
            <!-- Integrations -->
			<div>
                <div class="inline-block bg-primary-600 text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Enterprise System Integrations
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                    {#each integrations as tool}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-lg {tool.color} mb-3 flex items-center justify-center opacity-80 group-hover:opacity-100 transition-opacity">
                                <!-- Simple icon placeholder -->
                            </div> 
                            <span class="text-[10px] text-gray-400 font-medium text-center leading-tight">{tool.name}</span>
                        </div>
                    {/each}
                </div>
            </div>

            <!-- Capabilities -->
			<div>
                <div class="inline-block bg-primary-600 text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Process Mining Capabilities
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                     {#each capabilities as item}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-full border border-primary-500/40 mb-3 flex items-center justify-center text-primary-400 group-hover:text-primary-300 transition-colors">
                                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                    <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
                                </svg>
                            </div> 
                            <span class="text-[10px] text-gray-400 text-center leading-tight font-medium">{item}</span>
                        </div>
                    {/each}
                </div>
            </div>
		</div>
	</div>
</section>

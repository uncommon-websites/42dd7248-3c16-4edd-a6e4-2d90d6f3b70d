<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-12 leading-tight">
					Built for enterprise<br />
					security teams
				</h2>

				<div class="space-y-6">
					<div class="flex items-center gap-3 font-medium" style="color: oklch(0.696 0.17 162.48)">
						<div class="w-2 h-2 rounded-sm" style="background-color: oklch(0.696 0.17 162.48)"></div>
						Security Operations Centers
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8">
						Capture incident response workflows in real-time with AI-powered visual documentation that preserves tribal knowledge and accelerates threat detection.
					</p>

					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Cloud Security Teams
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						DevSecOps Engineers
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						IT Security Leaders
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Compliance Teams
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Threat Intelligence
					</div>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative bg-gradient-to-br from-[#0a0a0a] to-[#1a1a1a] border border-white/10">
                     <!-- Security Dashboard Mockup -->
                     <div class="absolute inset-0 p-8 flex flex-col">
                         <div class="text-xs text-gray-500 mb-6">M45 Security Dashboard</div>
                         
                         <!-- Alert Cards -->
                         <div class="space-y-3 mb-auto">
                             <div class="bg-red-500/10 border border-red-500/30 rounded-lg p-4">
                                 <div class="flex items-center gap-2 mb-2">
                                     <div class="w-2 h-2 bg-red-500 rounded-full animate-pulse"></div>
                                     <span class="text-xs font-medium text-red-400">Critical Alert</span>
                                 </div>
                                 <div class="text-sm text-gray-300">Unauthorized access detected in AWS S3</div>
                             </div>
                             
                             <div class="bg-yellow-500/10 border border-yellow-500/30 rounded-lg p-4">
                                 <div class="flex items-center gap-2 mb-2">
                                     <div class="w-2 h-2 bg-yellow-500 rounded-full"></div>
                                     <span class="text-xs font-medium text-yellow-400">Medium Priority</span>
                                 </div>
                                 <div class="text-sm text-gray-300">Configuration drift in Azure firewall</div>
                             </div>
                             
                             <div class="bg-green-500/10 border border-green-500/30 rounded-lg p-4">
                                 <div class="flex items-center gap-2 mb-2">
                                     <div class="w-2 h-2 bg-green-500 rounded-full"></div>
                                     <span class="text-xs font-medium text-green-400">Resolved</span>
                                 </div>
                                 <div class="text-sm text-gray-300">GCP security policy updated</div>
                             </div>
                         </div>
                         
                         <!-- Status Bar -->
                         <div class="flex items-center justify-between text-xs text-gray-500 mt-4 pt-4 border-t border-white/5">
                             <span>Last updated: 30s ago</span>
                             <span class="text-[oklch(0.696_0.17_162.48)]">Auto-documenting...</span>
                         </div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>

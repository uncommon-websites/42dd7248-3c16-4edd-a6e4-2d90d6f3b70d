<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6">
				Visual documentation<br />
				that thinks like your team
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				M45 captures, surfaces, and automates tribal knowledge across your entire security infrastructure.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: Capture -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Capture</h3>
					<p class="text-gray-400 text-sm">Visual documentation in real-time</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex items-center justify-center">
                         <!-- Abstract representation of workflow -->
                         <div class="w-full h-full border border-white/5 rounded-lg bg-[#0a0a0a] p-6 relative">
                             <div class="absolute top-1/2 left-8 -translate-y-1/2 text-gray-500 text-sm font-mono">
                                 Recording security workflow<br/>
                                 Auto-documenting steps >
                             </div>
                             <!-- Lines/Nodes -->
                             <div class="absolute right-12 top-12 bottom-12 w-1/3 border-l border-white/5 dashed"></div>
                             <div class="absolute right-12 top-1/2 w-8 h-px bg-white/10"></div>
                             <div class="absolute right-4 top-1/2 w-8 h-8 rounded bg-white/5 border border-white/10"></div>
                         </div>
                    </div>
                </div>
			</div>

			<!-- Card 2: Surface -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Surface</h3>
					<p class="text-gray-400 text-sm">Instant insights across your infrastructure</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <!-- Top stats row -->
                    <div class="flex gap-4 mb-6">
                        <div class="bg-red-500/10 p-4 rounded w-1/3 border border-red-500/20">
                            <div class="text-xs text-red-300 mb-1">Critical</div>
                            <div class="text-xl font-bold text-red-400">3 ↑</div>
                        </div>
                         <div class="bg-yellow-500/10 p-4 rounded w-1/3 border border-yellow-500/20">
                            <div class="text-xs text-yellow-300 mb-1">Medium</div>
                            <div class="text-xl font-bold text-yellow-400">12</div>
                        </div>
                         <div class="bg-green-500/10 p-4 rounded w-1/3 border border-green-500/20">
                            <div class="text-xs text-green-300 mb-1">Resolved</div>
                            <div class="text-xl font-bold text-green-400">47</div>
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
                             <path d="M0 45 C 20 40, 40 30, 60 25 S 80 15, 100 5" fill="none" stroke="#ef4444" stroke-width="2" />
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30" fill="none" stroke="#10b981" stroke-width="2" />
                             
                             <!-- Area under curve (fake) -->
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30 V 50 H 0 Z" fill="#10b981" fill-opacity="0.1" />
                         </svg>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Detect -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Detect</h3>
					<p class="text-gray-400 text-sm">AI-powered threat identification</p>
				</div>
                
                 <!-- Mockup Content - Code Editor Look -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4 font-mono text-[10px] leading-relaxed text-gray-400 shadow-inner">
                    <div class="flex gap-1.5 mb-4 border-b border-white/5 pb-2">
                        <div class="w-2 h-2 rounded-full bg-red-500/50"></div>
                        <div class="w-2 h-2 rounded-full bg-yellow-500/50"></div>
                        <div class="w-2 h-2 rounded-full bg-green-500/50"></div>
                    </div>
                    <div class="space-y-1">
                        <div class="text-purple-400">from <span class="text-white">m45_security</span> import <span class="text-yellow-300">ThreatDetector</span></div>
                        <div class="text-purple-400">from <span class="text-white">cloud</span> import <span class="text-yellow-300">AWS, Azure, GCP</span></div>
                        <br/>
                         <div class="text-purple-400">class <span class="text-yellow-300">SecurityMonitor</span>:</div>
                         <div class="pl-4 text-gray-600">"""Real-time threat detection"""</div>
                         <div class="pl-4 text-purple-400">def <span class="text-blue-400">scan_infrastructure</span>(self):</div>
                         <div class="pl-8 text-white">threats = self.detector.analyze()</div>
                         <div class="pl-8 text-white">self.alert_team(threats)</div>
                         <div class="pl-4 text-purple-400">def <span class="text-blue-400">capture_context</span>(self):</div>
                         <div class="pl-8 text-white">return self.visual_docs.generate()</div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Automate -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Automate</h3>
					<p class="text-gray-400 text-sm">Workflow automation for security teams</p>
				</div>
                
                 <!-- Mockup Content - Action Card -->
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-xl p-5 w-full shadow-2xl relative">
                        <!-- Glow effect -->
                        <div class="absolute -inset-1 bg-gradient-to-r from-blue-500/20 to-purple-500/20 blur opacity-50"></div>
                        
                        <div class="relative bg-[#1a1a1a] rounded-xl">
                            <div class="flex items-center gap-3 mb-4">
                                <div class="w-8 h-8 rounded bg-white/10 flex items-center justify-center shrink-0">
                                    <div class="w-4 h-4 bg-white rotate-45"></div>
                                </div>
                                <div>
                                    <div class="font-medium text-xs text-white">Critical alert detected in AWS</div>
                                    <div class="text-[10px] text-gray-500">Auto-documenting incident response</div>
                                </div>
                            </div>
                            <div class="h-1.5 w-full bg-white/10 rounded-full overflow-hidden">
                                <div class="h-full bg-blue-500 w-2/3"></div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Unify -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Unify</h3>
					<p class="text-gray-400 text-sm">Single pane of glass across all clouds</p>
				</div>
                
                 <!-- Mockup Content - Search/Result -->
                <div class="flex-1 relative flex flex-col gap-4">
                    <div class="bg-[#1a1a1a] rounded-lg p-4 text-xs text-gray-300 border border-white/5">
                        Here's your unified security posture across AWS, Azure, and GCP.
                    </div>
                    
                    <div class="flex-1 bg-gradient-to-br from-[#1a1a1a] to-black border border-white/10 rounded-lg overflow-hidden flex flex-col">
                         <div class="relative h-32 bg-gradient-to-r from-purple-500/20 to-blue-500/20 flex items-center justify-center">
                             <div class="text-center">
                                 <div class="text-xs font-semibold text-white">Multi-Cloud Dashboard</div>
                                 <div class="text-[10px] text-gray-400">3 environments monitored</div>
                             </div>
                         </div>
                         <div class="p-4 flex items-center justify-between mt-auto">
                             <div class="text-[10px] text-gray-500">Updated 30s ago</div>
                             <button class="bg-white text-black text-[10px] font-bold px-3 py-1.5 rounded-full flex items-center gap-1 hover:bg-gray-200 transition-colors">
                                 <Play size={10} fill="currentColor" /> View
                             </button>
                         </div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>

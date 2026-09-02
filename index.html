<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator Preț Print 3D - Bambu Lab P2S</title>
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Chart.js for Donut Chart -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script>
        // Configure Tailwind to use the 'class' strategy for dark mode
        tailwind.config = {
            darkMode: 'class',
        }
    </script>
    <style>
        /* Custom styles for sliders */
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
        }
        input[type=range]:focus {
            outline: none;
        }
        
        /* Light mode slider track */
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 8px;
            cursor: pointer;
            background: #e2e8f0;
            border-radius: 9999px;
            transition: background 0.2s;
        }
        /* Dark mode slider track */
        html.dark input[type=range]::-webkit-slider-runnable-track {
            background: #475569;
        }
        
        input[type=range]::-webkit-slider-thumb {
            height: 20px;
            width: 20px;
            border-radius: 50%;
            background: #3b82f6;
            cursor: pointer;
            -webkit-appearance: none;
            margin-top: -6px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.3);
        }
        
        input[type=range]:focus::-webkit-slider-runnable-track {
            background: #cbd5e1;
        }
        html.dark input[type=range]:focus::-webkit-slider-runnable-track {
            background: #64748b;
        }
        
        /* Modern Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: transparent; 
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1; 
            border-radius: 4px;
        }
        html.dark ::-webkit-scrollbar-thumb {
            background: #475569;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8; 
        }
    </style>
</head>
<body class="bg-slate-50 dark:bg-slate-950 text-slate-800 dark:text-slate-200 font-sans min-h-screen p-4 md:p-8 transition-colors duration-200">
    <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-8">
        
        <!-- Left Column: Inputs Form -->
        <div class="lg:col-span-7 space-y-6">
            <div class="bg-white dark:bg-slate-900 rounded-2xl shadow-sm border border-slate-200 dark:border-slate-800 p-6 md:p-8 transition-colors duration-200">
                <div class="flex justify-between items-start border-b border-slate-100 dark:border-slate-800 pb-6 mb-6">
                    <div>
                        <h1 class="text-3xl font-bold text-slate-900 dark:text-white tracking-tight">Calculator Preț Print 3D</h1>
                        <p class="text-slate-500 dark:text-slate-400 mt-2 flex items-center gap-2">
                            <svg class="w-5 h-5 text-blue-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                            Optimizat pentru Bambu Lab P2S
                        </p>
                    </div>
                    <!-- Dark Mode Toggle Button -->
                    <button id="themeToggle" class="p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:bg-slate-200 dark:hover:bg-slate-700 transition-colors" aria-label="Toggle Dark Mode">
                        <svg id="themeIconLight" class="w-5 h-5 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z"></path></svg>
                        <svg id="themeIconDark" class="w-5 h-5 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z"></path></svg>
                    </button>
                </div>

                <form id="calculatorForm" class="space-y-8">
                    
                    <!-- Section 1: Materials -->
                    <div class="space-y-4">
                        <div class="flex items-center gap-2 border-b border-slate-100 dark:border-slate-800 pb-2">
                            <div class="bg-blue-100 dark:bg-blue-900/50 text-blue-600 dark:text-blue-400 rounded-full w-8 h-8 flex items-center justify-center font-bold">1</div>
                            <h2 class="text-xl font-semibold text-slate-800 dark:text-slate-200">Material & Consum</h2>
                        </div>
                        
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 pt-2">
                            <div>
                                <label for="filamentType" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Tip Filament</label>
                                <select id="filamentType" class="block w-full pl-3 pr-10 py-2.5 text-base border-slate-300 dark:border-slate-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 sm:text-sm rounded-lg border bg-white dark:bg-slate-800 dark:text-white shadow-sm cursor-pointer hover:bg-slate-50 dark:hover:bg-slate-700 transition-colors">
                                    <option value="120">PLA (~120W)</option>
                                    <option value="120">PLA-CF (~120W)</option>
                                    <option value="130">TPU (~130W)</option>
                                    <option value="150">PETG (~150W)</option>
                                    <option value="150">PETG-CF (~150W)</option>
                                    <option value="250">ABS / ASA (~250W)</option>
                                    <option value="250">PA-CF / ASA-CF (~250W)</option>
                                </select>
                                <p class="text-xs text-slate-500 dark:text-slate-400 mt-1.5">Influențează calculul consumului de energie.</p>
                            </div>

                            <div>
                                <label for="pricePerKg" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Preț Filament / kg</label>
                                <div class="relative rounded-lg shadow-sm">
                                    <input type="number" id="pricePerKg" value="95" min="0" step="1" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-blue-500 focus:border-blue-500 block w-full pl-4 pr-12 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                    <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                        <span class="text-slate-500 dark:text-slate-400 font-medium">RON</span>
                                    </div>
                                </div>
                            </div>

                            <div>
                                <label for="quantity" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Cantitate Folosită</label>
                                <div class="relative rounded-lg shadow-sm">
                                    <input type="number" id="quantity" value="150" min="0" step="1" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-blue-500 focus:border-blue-500 block w-full pl-4 pr-12 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                    <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                        <span class="text-slate-500 dark:text-slate-400 font-medium">g</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Section 2: Time & Labor -->
                    <div class="space-y-4 pt-4">
                        <div class="flex items-center gap-2 border-b border-slate-100 dark:border-slate-800 pb-2">
                            <div class="bg-emerald-100 dark:bg-emerald-900/50 text-emerald-600 dark:text-emerald-400 rounded-full w-8 h-8 flex items-center justify-center font-bold">2</div>
                            <h2 class="text-xl font-semibold text-slate-800 dark:text-slate-200">Timp & Manoperă</h2>
                        </div>
                        
                        <div class="space-y-5 pt-2">
                            <!-- Print Time -->
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">Timp Printare (Ore)</label>
                                    <div class="flex items-center gap-4">
                                        <input type="range" id="printTimeHoursSlider" min="0" max="100" value="2" class="flex-1">
                                        <div class="relative w-24 shrink-0 shadow-sm rounded-lg">
                                            <input type="number" id="printTimeHours" value="2" min="0" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 block w-full px-2 py-2 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg border text-center font-medium">
                                        </div>
                                    </div>
                                </div>
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">Minute</label>
                                    <div class="flex items-center gap-4">
                                        <input type="range" id="printTimeMinutesSlider" min="0" max="59" value="30" class="flex-1">
                                        <div class="relative w-24 shrink-0 shadow-sm rounded-lg">
                                            <input type="number" id="printTimeMinutes" value="30" min="0" max="59" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 block w-full px-2 py-2 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg border text-center font-medium">
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <!-- Labor Customization -->
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 border-t border-slate-50 dark:border-slate-800 pt-5">
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">Timp Customizare (Min)</label>
                                    <div class="flex items-center gap-4">
                                        <input type="range" id="laborPrepTimeSlider" min="0" max="120" value="0" class="flex-1">
                                        <div class="relative w-24 shrink-0 shadow-sm rounded-lg">
                                            <input type="number" id="laborPrepTime" value="0" min="0" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 block w-full px-2 py-2 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg border text-center font-medium">
                                        </div>
                                    </div>
                                    <p class="text-xs text-slate-500 dark:text-slate-400 mt-1.5">Modelare, slicing, pregătire fișier.</p>
                                </div>
                                <div>
                                    <label for="laborPrepRate" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Preț Customizare / oră</label>
                                    <div class="relative rounded-lg shadow-sm">
                                        <input type="number" id="laborPrepRate" value="100" min="0" step="1" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 block w-full pl-4 pr-12 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                        <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                            <span class="text-slate-500 dark:text-slate-400 font-medium">RON</span>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <!-- Labor Post-processing -->
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 border-t border-slate-50 dark:border-slate-800 pt-5">
                                <div>
                                    <label class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-2">Timp Post-procesare (Min)</label>
                                    <div class="flex items-center gap-4">
                                        <input type="range" id="laborPostTimeSlider" min="0" max="120" value="0" class="flex-1">
                                        <div class="relative w-24 shrink-0 shadow-sm rounded-lg">
                                            <input type="number" id="laborPostTime" value="0" min="0" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 block w-full px-2 py-2 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg border text-center font-medium">
                                        </div>
                                    </div>
                                    <p class="text-xs text-slate-500 dark:text-slate-400 mt-1.5">Curățare suporți, asamblare finisaj.</p>
                                </div>
                                <div>
                                    <label for="laborPostRate" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Preț Post-procesare / oră</label>
                                    <div class="relative rounded-lg shadow-sm">
                                        <input type="number" id="laborPostRate" value="50" min="0" step="1" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 block w-full pl-4 pr-12 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                        <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                            <span class="text-slate-500 dark:text-slate-400 font-medium">RON</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Section 3: Packaging -->
                    <div class="space-y-4 pt-4">
                        <div class="flex items-center gap-2 border-b border-slate-100 dark:border-slate-800 pb-2">
                            <div class="bg-amber-100 dark:bg-amber-900/50 text-amber-600 dark:text-amber-400 rounded-full w-8 h-8 flex items-center justify-center font-bold">3</div>
                            <h2 class="text-xl font-semibold text-slate-800 dark:text-slate-200">Ambalare & Logistică</h2>
                        </div>
                        
                        <div class="pt-2">
                            <label for="packagingCost" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Cost Fix Ambalaj / Colet</label>
                            <div class="relative rounded-lg shadow-sm w-full sm:w-1/2">
                                <input type="number" id="packagingCost" value="0" min="0" step="0.5" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-amber-500 focus:border-amber-500 block w-full pl-4 pr-12 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                    <span class="text-slate-500 dark:text-slate-400 font-medium">RON</span>
                                </div>
                            </div>
                            <p class="text-xs text-slate-500 dark:text-slate-400 mt-1.5">Cutii de carton, folie cu bule, etichete etc.</p>
                        </div>
                    </div>

                    <!-- Section 4: Costs & Profit -->
                    <div class="space-y-4 pt-4">
                        <div class="flex items-center gap-2 border-b border-slate-100 dark:border-slate-800 pb-2">
                            <div class="bg-purple-100 dark:bg-purple-900/50 text-purple-600 dark:text-purple-400 rounded-full w-8 h-8 flex items-center justify-center font-bold">4</div>
                            <h2 class="text-xl font-semibold text-slate-800 dark:text-slate-200">Profit</h2>
                        </div>
                        
                        <div class="space-y-5 pt-2">
                            <!-- Profit Margin -->
                            <div class="pt-2">
                                <div class="flex justify-between items-center mb-2">
                                    <label class="text-sm font-medium text-slate-700 dark:text-slate-300">Marjă Profit Comercial</label>
                                    <span class="text-sm font-bold text-purple-700 dark:text-purple-300 bg-purple-50 dark:bg-purple-900/40 px-2 py-0.5 rounded" id="profitLabel">30%</span>
                                </div>
                                <div class="flex items-center gap-4">
                                    <input type="range" id="profitSlider" min="0" max="300" value="30" class="flex-1">
                                    <div class="relative w-24 shrink-0 shadow-sm rounded-lg">
                                        <input type="number" id="profitInput" value="30" min="0" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-purple-500 focus:border-purple-500 block w-full px-2 py-2 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg border text-center font-medium">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Advanced Configs Accordion -->
                    <div class="pt-6">
                        <details class="group bg-slate-50 dark:bg-slate-800/50 rounded-xl border border-slate-200 dark:border-slate-700 overflow-hidden">
                            <summary class="flex items-center justify-between p-4 cursor-pointer select-none hover:bg-slate-100 dark:hover:bg-slate-800 transition-colors">
                                <div class="flex items-center gap-2">
                                    <svg class="w-5 h-5 text-slate-500 dark:text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                                    <span class="font-semibold text-slate-700 dark:text-slate-200">Configurări Avansate</span>
                                </div>
                                <span class="transition-transform group-open:rotate-180 text-slate-400">
                                    <svg fill="none" height="24" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" width="24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"></path></svg>
                                </span>
                            </summary>
                            
                            <div class="p-4 border-t border-slate-200 dark:border-slate-700 bg-white dark:bg-slate-900">
                                <div class="grid grid-cols-1 sm:grid-cols-3 gap-5">
                                    <!-- Failure Risk Input -->
                                    <div>
                                        <label for="riskInput" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Risc Eșec</label>
                                        <div class="relative rounded-lg shadow-sm">
                                            <input type="number" id="riskInput" value="5" min="0" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-slate-500 focus:border-slate-500 block w-full pl-4 pr-8 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                            <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                                <span class="text-slate-500 dark:text-slate-400 font-medium text-xs">%</span>
                                            </div>
                                        </div>
                                    </div>

                                    <div>
                                        <label for="electricityCost" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Cost Curent</label>
                                        <div class="relative rounded-lg shadow-sm">
                                            <input type="number" id="electricityCost" value="1.16" min="0" step="0.01" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-slate-500 focus:border-slate-500 block w-full pl-4 pr-14 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                            <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                                <span class="text-slate-500 dark:text-slate-400 font-medium text-xs">RON/kWh</span>
                                            </div>
                                        </div>
                                    </div>

                                    <div>
                                        <label for="printerWearCost" class="block text-sm font-medium text-slate-700 dark:text-slate-300 mb-1">Amortizare</label>
                                        <div class="relative rounded-lg shadow-sm">
                                            <input type="number" id="printerWearCost" value="2.5" min="0" step="0.1" class="bg-white dark:bg-slate-800 dark:text-white focus:ring-2 focus:ring-slate-500 focus:border-slate-500 block w-full pl-4 pr-12 sm:text-sm border-slate-300 dark:border-slate-700 rounded-lg py-2.5 border hover:border-slate-400 dark:hover:border-slate-600 transition-colors">
                                            <div class="absolute inset-y-0 right-0 pr-3 flex items-center pointer-events-none">
                                                <span class="text-slate-500 dark:text-slate-400 font-medium text-xs">RON/h</span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <p class="text-xs text-slate-500 dark:text-slate-400 mt-3">* Amortizarea a fost calculată la 4500 RON / 2000 ore = 2.25 RON/h + 0.25 RON/h (mentenanță & consumabile).</p>
                                <p class="text-xs text-slate-500 dark:text-slate-400 mt-1">* Pentru filamentele abrazive (care conțin CF), costul de uzură crește automat cu 50% pentru a acoperi uzura prematură a duzei și extruderului.</p>
                                <p class="text-xs text-slate-500 dark:text-slate-400 mt-1">* Riscul de eșec adaugă un procent de siguranță peste costurile de producție directe.</p>
                            </div>
                        </details>
                    </div>
                </form>
            </div>
        </div>

        <!-- Right Column: Results Panel (Sticky) -->
        <div class="lg:col-span-5 relative">
            <div class="bg-slate-900 dark:bg-slate-900 rounded-2xl shadow-xl text-slate-100 overflow-hidden sticky top-8 border border-slate-800 dark:border-slate-700">
                <!-- Final Price Header -->
                <div class="bg-gradient-to-br from-slate-800 to-slate-900 dark:from-slate-800/80 dark:to-slate-950 p-8 text-center border-b border-slate-700 dark:border-slate-800">
                    <p class="text-slate-400 text-sm font-semibold uppercase tracking-widest mb-2">Preț Final Recomandat</p>
                    <div class="flex justify-center items-end gap-2">
                        <span id="finalPriceDisplay" class="text-5xl lg:text-6xl font-bold text-emerald-400 tabular-nums tracking-tighter">0.00</span>
                        <span class="text-xl text-emerald-500/70 mb-2 font-medium">RON</span>
                    </div>
                    <button onclick="copyToClipboard()" class="mt-4 px-4 py-2 bg-slate-700 hover:bg-slate-600 text-slate-200 text-sm font-medium rounded-lg transition-colors flex items-center justify-center gap-2 mx-auto">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v3m2 4H10m0 0l3-3m-3 3l3 3"></path></svg>
                        Copiază Oferta
                    </button>
                    <div id="copyToast" class="text-emerald-400 text-xs mt-2 opacity-0 transition-opacity h-4">Copiat în clipboard!</div>
                </div>

                <!-- Detailed Breakdown -->
                <div class="p-6 space-y-4">
                    <h3 class="text-lg font-semibold text-white mb-4 flex items-center gap-2">
                        <svg class="w-5 h-5 text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 17v-2m3 2v-4m3 4v-6m2 10H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                        Defalcare Costuri
                    </h3>
                    
                    <div class="space-y-3 font-medium text-sm">
                        <div class="flex justify-between items-center group">
                            <span class="text-slate-400 group-hover:text-slate-300 transition-colors flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-blue-500"></span>Material:</span>
                            <span id="costMaterialDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                        <div class="flex justify-between items-center group">
                            <span class="text-slate-400 group-hover:text-slate-300 transition-colors flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-yellow-500"></span>Energie:</span>
                            <span id="costEnergieDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                        <div class="flex justify-between items-center group">
                            <span class="text-slate-400 group-hover:text-slate-300 transition-colors flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-orange-500"></span>Uzură Imprimantă <span id="wearNotice" class="text-orange-400 text-xs ml-1 hidden" title="Cost suplimentar pentru uzura abrazivă">(+Abraziv)</span>:</span>
                            <span id="costUzuraDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                        <div class="flex justify-between items-center group">
                            <span class="text-slate-400 group-hover:text-slate-300 transition-colors flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-emerald-500"></span>Customizare:</span>
                            <span id="costPrepDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                        <div class="flex justify-between items-center group">
                            <span class="text-slate-400 group-hover:text-slate-300 transition-colors flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-teal-500"></span>Post-procesare:</span>
                            <span id="costPostDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                        <div class="flex justify-between items-center group">
                            <span class="text-slate-400 group-hover:text-slate-300 transition-colors flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-amber-500"></span>Ambalare:</span>
                            <span id="costAmbalareDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                        
                        <div class="pt-2 mt-2 border-t border-slate-700/50">
                            <div class="flex justify-between items-center text-slate-300">
                                <span>Subtotal Direct:</span>
                                <span id="subtotalDisplay" class="tabular-nums">0.00 RON</span>
                            </div>
                        </div>
                        
                        <div class="flex justify-between items-center text-rose-400/90 group pt-1">
                            <span class="flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-rose-500"></span>Risc Eșec (<span id="displayRiskPercent">5</span>%):</span>
                            <span id="costRiscDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                        
                        <div class="pt-2 mt-2 border-t border-slate-700/50">
                            <div class="flex justify-between items-center text-slate-200">
                                <span>Cost Total Producție:</span>
                                <span id="costTotalDisplay" class="tabular-nums font-semibold">0.00 RON</span>
                            </div>
                        </div>

                        <div class="flex justify-between items-center text-purple-400/90 pt-1">
                            <span class="flex items-center gap-2"><span class="w-2.5 h-2.5 rounded-full bg-purple-500"></span>Profit Adăugat (<span id="displayProfitPercent">30</span>%):</span>
                            <span id="valoareProfitDisplay" class="tabular-nums">0.00 RON</span>
                        </div>
                    </div>
                </div>

                <!-- Cost Allocation Chart -->
                <div class="px-6 pb-8">
                    <div class="relative h-48 w-full flex items-center justify-center">
                        <canvas id="costChart"></canvas>
                    </div>
                </div>

                <!-- Metrics Grid -->
                <div class="bg-slate-800 dark:bg-slate-800/80 p-6 border-t border-slate-700 dark:border-slate-800">
                    <h3 class="text-sm font-semibold text-slate-300 mb-4 uppercase tracking-wider">Metrici Eficiență</h3>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-slate-900/50 p-3 rounded-lg border border-slate-700/50">
                            <p class="text-xs text-slate-400 mb-1">Preț / Gram (Vânzare)</p>
                            <p id="statPricePerGram" class="text-lg font-semibold text-blue-400 tabular-nums">0.00 <span class="text-xs text-blue-500/70 font-normal">lei</span></p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-lg border border-slate-700/50">
                            <p class="text-xs text-slate-400 mb-1">Cost / Gram (Producție)</p>
                            <p id="statCostPerGram" class="text-lg font-semibold text-slate-200 tabular-nums">0.00 <span class="text-xs text-slate-500 font-normal">lei</span></p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-lg border border-slate-700/50">
                            <p class="text-xs text-slate-400 mb-1">Generare Venit / Oră</p>
                            <p id="statPricePerHour" class="text-lg font-semibold text-emerald-400 tabular-nums">0.00 <span class="text-xs text-emerald-500/70 font-normal">lei</span></p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-lg border border-slate-700/50">
                            <p class="text-xs text-slate-400 mb-1">Marjă Profit Efectivă</p>
                            <p id="statEffectiveMargin" class="text-lg font-semibold text-purple-400 tabular-nums">0.0%</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            
            let costChart = null;

            // --- Dark Mode Logic ---
            const themeToggleBtn = document.getElementById('themeToggle');
            const iconLight = document.getElementById('themeIconLight');
            const iconDark = document.getElementById('themeIconDark');
            
            // Check for saved theme or system preference
            if (localStorage.theme === 'dark' || (!('theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
                document.documentElement.classList.add('dark');
                iconLight.classList.remove('hidden');
            } else {
                document.documentElement.classList.remove('dark');
                iconDark.classList.remove('hidden');
            }

            themeToggleBtn.addEventListener('click', () => {
                const isDark = document.documentElement.classList.toggle('dark');
                if (isDark) {
                    localStorage.theme = 'dark';
                    iconLight.classList.remove('hidden');
                    iconDark.classList.add('hidden');
                } else {
                    localStorage.theme = 'light';
                    iconLight.classList.add('hidden');
                    iconDark.classList.remove('hidden');
                }
            });

            // --- Sync Sliders and Inputs ---
            function syncInputAndSlider(sliderId, inputId, labelId = null, suffix = '') {
                const slider = document.getElementById(sliderId);
                const input = document.getElementById(inputId);
                const label = labelId ? document.getElementById(labelId) : null;

                if(!slider || !input) return;

                slider.addEventListener('input', (e) => {
                    input.value = e.target.value;
                    if(label) label.textContent = e.target.value + suffix;
                    calculatePrice();
                });
                
                input.addEventListener('input', (e) => {
                    let val = parseFloat(e.target.value);
                    if(isNaN(val)) val = 0;
                    slider.value = val; 
                    if(label) label.textContent = val + suffix;
                    calculatePrice();
                });
            }

            // Init syncs
            syncInputAndSlider('printTimeHoursSlider', 'printTimeHours');
            syncInputAndSlider('printTimeMinutesSlider', 'printTimeMinutes');
            syncInputAndSlider('laborPrepTimeSlider', 'laborPrepTime');
            syncInputAndSlider('laborPostTimeSlider', 'laborPostTime');
            syncInputAndSlider('profitSlider', 'profitInput', 'profitLabel', '%');

            // --- Add event listeners for auto-calculation ---
            const inputIds = [
                'filamentType', 'pricePerKg', 'quantity', 
                'laborPrepRate', 'laborPostRate', 'packagingCost',
                'electricityCost', 'printerWearCost', 'riskInput'
            ];
            
            inputIds.forEach(id => {
                const el = document.getElementById(id);
                if(el) {
                    el.addEventListener('input', calculatePrice);
                    if(el.tagName === 'SELECT') el.addEventListener('change', calculatePrice);
                }
            });

            // Currency Formatter
            function formatCurrency(num) {
                return num.toFixed(2) + ' RON';
            }

            // --- Main Calculator Function ---
            function calculatePrice() {
                // 1. Get Values
                const filamentWatts = parseFloat(document.getElementById('filamentType').value) || 120;
                const pKg = parseFloat(document.getElementById('pricePerKg').value) || 0;
                const qGrams = parseFloat(document.getElementById('quantity').value) || 0;
                
                const hrs = parseFloat(document.getElementById('printTimeHours').value) || 0;
                const mins = parseFloat(document.getElementById('printTimeMinutes').value) || 0;
                const totalPrintHours = hrs + (mins / 60);

                const laborPrepMins = parseFloat(document.getElementById('laborPrepTime').value) || 0;
                const laborPrepRate = parseFloat(document.getElementById('laborPrepRate').value) || 0;
                const prepCost = (laborPrepMins / 60) * laborPrepRate;

                const laborPostMins = parseFloat(document.getElementById('laborPostTime').value) || 0;
                const laborPostRate = parseFloat(document.getElementById('laborPostRate').value) || 0;
                const postCost = (laborPostMins / 60) * laborPostRate;
                
                const totalLaborCost = prepCost + postCost;
                
                const packagingCost = parseFloat(document.getElementById('packagingCost').value) || 0;

                const electRate = parseFloat(document.getElementById('electricityCost').value) || 0;
                const wearRate = parseFloat(document.getElementById('printerWearCost').value) || 0;
                
                const riskPct = parseFloat(document.getElementById('riskInput').value) || 0;
                const profitPct = parseFloat(document.getElementById('profitInput').value) || 0;

                // 2. Calculations
                
                // Verifică dacă filamentul este abraziv
                const filamentSelect = document.getElementById('filamentType');
                const filamentText = filamentSelect.options[filamentSelect.selectedIndex].text;
                const isAbrasive = filamentText.includes('-CF');
                
                // Multiplicator uzură (50% în plus pentru filamente cu fibră de carbon)
                const actualWearRate = isAbrasive ? (wearRate * 1.5) : wearRate;
                
                // Afișează badge-ul de avertizare abraziv dacă e cazul
                const wearNotice = document.getElementById('wearNotice');
                if (wearNotice) {
                    isAbrasive ? wearNotice.classList.remove('hidden') : wearNotice.classList.add('hidden');
                }

                // Direct Costs
                const materialCost = (pKg / 1000) * qGrams;
                
                // Energy: Power(W) * Time(h) / 1000 = kWh
                const energyKwh = (filamentWatts * totalPrintHours) / 1000;
                const energyCost = energyKwh * electRate;
                
                const wearCost = actualWearRate * totalPrintHours;

                const directSubtotal = materialCost + energyCost + wearCost + totalLaborCost + packagingCost;

                // Risk Cost
                const riskCost = directSubtotal * (riskPct / 100);

                // Total Cost (Break-even)
                const totalCost = directSubtotal + riskCost;

                // Profit & Final Price
                const profitAmount = totalCost * (profitPct / 100);
                const finalPrice = totalCost + profitAmount;

                // Metrics
                const costPerGram = qGrams > 0 ? (totalCost / qGrams) : 0;
                const pricePerGram = qGrams > 0 ? (finalPrice / qGrams) : 0;
                const revenuePerHour = totalPrintHours > 0 ? (finalPrice / totalPrintHours) : 0;
                // Effective margin from the final price (not the markup percentage)
                const effectiveMargin = finalPrice > 0 ? (profitAmount / finalPrice) * 100 : 0;

                // 3. Update DOM
                
                // Breakdown
                document.getElementById('costMaterialDisplay').textContent = formatCurrency(materialCost);
                document.getElementById('costEnergieDisplay').textContent = formatCurrency(energyCost);
                document.getElementById('costUzuraDisplay').textContent = formatCurrency(wearCost);
                document.getElementById('costPrepDisplay').textContent = formatCurrency(prepCost);
                document.getElementById('costPostDisplay').textContent = formatCurrency(postCost);
                document.getElementById('costAmbalareDisplay').textContent = formatCurrency(packagingCost);
                
                document.getElementById('subtotalDisplay').textContent = formatCurrency(directSubtotal);
                
                document.getElementById('displayRiskPercent').textContent = riskPct;
                document.getElementById('costRiscDisplay').textContent = formatCurrency(riskCost);
                
                document.getElementById('costTotalDisplay').textContent = formatCurrency(totalCost);
                
                document.getElementById('displayProfitPercent').textContent = profitPct;
                document.getElementById('valoareProfitDisplay').textContent = formatCurrency(profitAmount);

                // Main Price (Animate slightly)
                const priceDisplay = document.getElementById('finalPriceDisplay');
                priceDisplay.style.opacity = 0.7;
                setTimeout(() => {
                    priceDisplay.textContent = finalPrice.toFixed(2);
                    priceDisplay.style.opacity = 1;
                }, 50);

                // Metrics
                document.getElementById('statCostPerGram').textContent = costPerGram.toFixed(2);
                document.getElementById('statPricePerGram').textContent = pricePerGram.toFixed(2);
                document.getElementById('statPricePerHour').textContent = revenuePerHour.toFixed(2);
                document.getElementById('statEffectiveMargin').textContent = effectiveMargin.toFixed(1) + '%';

                // --- Update Cost Allocation Chart ---
                const chartData = [materialCost, energyCost, wearCost, prepCost, postCost, packagingCost, riskCost, profitAmount];
                
                if (costChart) {
                    costChart.data.datasets[0].data = chartData;
                    costChart.update();
                } else {
                    const ctx = document.getElementById('costChart').getContext('2d');
                    costChart = new Chart(ctx, {
                        type: 'doughnut',
                        data: {
                            labels: ['Material', 'Energie', 'Uzură', 'Customizare', 'Post-procesare', 'Ambalare', 'Risc Eșec', 'Profit'],
                            datasets: [{
                                data: chartData,
                                backgroundColor: [
                                    '#3b82f6', // blue-500
                                    '#eab308', // yellow-500
                                    '#f97316', // orange-500
                                    '#10b981', // emerald-500
                                    '#14b8a6', // teal-500
                                    '#f59e0b', // amber-500
                                    '#f43f5e', // rose-500
                                    '#a855f7'  // purple-500
                                ],
                                borderWidth: 0, // Scoatem marginea alba default a chart.js
                                hoverOffset: 6
                            }]
                        },
                        options: {
                            responsive: true,
                            maintainAspectRatio: false,
                            cutout: '75%', // Grosimea inelului
                            plugins: {
                                legend: {
                                    display: false // Ascundem legenda deoarece lista de deasupra face deja acest lucru
                                },
                                tooltip: {
                                    backgroundColor: 'rgba(15, 23, 42, 0.9)', // slate-900 transparent
                                    titleColor: '#f1f5f9', // slate-100
                                    bodyColor: '#f1f5f9',
                                    borderColor: '#334155', // slate-700
                                    borderWidth: 1,
                                    padding: 10,
                                    callbacks: {
                                        label: function(context) {
                                            let label = context.label || '';
                                            if (label) {
                                                label += ': ';
                                            }
                                            if (context.parsed !== null) {
                                                label += context.parsed.toFixed(2) + ' RON';
                                            }
                                            return label;
                                        }
                                    }
                                }
                            }
                        }
                    });
                }
            }

            // Expose copy function to window
            window.copyToClipboard = function() {
                const finalPrice = document.getElementById('finalPriceDisplay').textContent;
                const material = document.getElementById('filamentType').options[document.getElementById('filamentType').selectedIndex].text.split('(')[0].trim();
                const weight = document.getElementById('quantity').value;
                const timeH = document.getElementById('printTimeHours').value;
                const timeM = document.getElementById('printTimeMinutes').value;
                
                const text = `Ofertă Print 3D\nMaterial: ${material} (${weight}g)\nTimp estimat: ${timeH}h ${timeM}m\nPreț: ${finalPrice} RON`;
                
                // Fallback for iFrame environments
                const textArea = document.createElement("textarea");
                textArea.value = text;
                document.body.appendChild(textArea);
                textArea.select();
                try {
                    document.execCommand('copy');
                    const toast = document.getElementById('copyToast');
                    toast.style.opacity = '1';
                    setTimeout(() => toast.style.opacity = '0', 2000);
                } catch (err) {
                    console.error('Failed to copy', err);
                }
                document.body.removeChild(textArea);
            };

            // Run initial calculation
            calculatePrice();
        });
    </script>
</body>
</html>

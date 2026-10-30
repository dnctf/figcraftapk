<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FigCraft for Android (APK Release)</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased selection:bg-indigo-500 selection:text-white">

    <!-- Header / Hero Section -->
    <header class="relative overflow-hidden bg-gradient-to-b from-slate-800 to-slate-900 border-b border-slate-800">
        <div class="max-w-4xl mx-auto px-6 py-16 text-center">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-indigo-500/10 text-indigo-400 border border-indigo-500/20 text-sm font-medium mb-6">
                <i class="fa-solid fa-robot"></i> Android Port & Release
            </div>
            <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight mb-4 text-white">
                FigCraft for Android
            </h1>
            <p class="text-lg text-slate-400 max-w-2xl mx-auto mb-8">
                Bringing the powerful FigCraft experience directly to your Android devices through an optimized wrapper architecture.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#installation" class="px-6 py-3 rounded-xl bg-indigo-600 hover:bg-indigo-500 text-white font-semibold shadow-lg shadow-indigo-600/30 transition-all flex items-center gap-2">
                    <i class="fa-solid fa-download"></i> Download APK
                </a>
                <a href="#architecture" class="px-6 py-3 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold border border-slate-700 transition-all flex items-center gap-2">
                    <i class="fa-solid fa-cogs"></i> Architecture
                </a>
            </div>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="max-w-4xl mx-auto px-6 py-12 space-y-12">

        <!-- Architecture Section -->
        <section id="architecture" class="bg-slate-800/50 border border-slate-800 rounded-2xl p-8 backdrop-blur-sm">
            <div class="flex items-center gap-3 mb-6">
                <div class="p-3 bg-indigo-500/10 text-indigo-400 rounded-xl">
                    <i class="fa-solid fa-network-wired text-xl"></i>
                </div>
                <h2 class="text-2xl font-bold text-white">Architecture & Fork Porting Methodology</h2>
            </div>
            
            <p class="text-slate-300 mb-6 leading-relaxed">
                This Android release is built using a robust <strong>Fork-Porting Methodology</strong> to ensure seamless mobile compatibility while maintaining strict fidelity to the upstream project.
            </p>

            <div class="space-y-6">
                <div class="flex gap-4">
                    <div class="flex-shrink-0 w-8 h-8 rounded-full bg-indigo-600/20 border border-indigo-500/30 flex items-center justify-center text-indigo-400 font-bold text-sm">1</div>
                    <div>
                        <h3 class="text-lg font-semibold text-white mb-1">Upstream Alignment</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">The core web application code is forked and synchronized with the latest upstream repository releases to inherit ongoing feature updates, bug fixes, and performance improvements.</p>
                    </div>
                </div>

                <div class="flex gap-4">
                    <div class="flex-shrink-0 w-8 h-8 rounded-full bg-indigo-600/20 border border-indigo-500/30 flex items-center justify-center text-indigo-400 font-bold text-sm">2</div>
                    <div>
                        <h3 class="text-lg font-semibold text-white mb-1">Mobile Adaptation Layer</h3>
                        <ul class="mt-2 space-y-2 text-slate-400 text-sm">
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-indigo-400 mt-1"></i>
                                <span><strong>WebView Wrapper & Native Bridge:</strong> Encapsulates the web client inside an optimized Android WebView container equipped with custom asset caching and hardware acceleration flags.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-indigo-400 mt-1"></i>
                                <span><strong>Touch & Gesture Mapping:</strong> Translates native touch, pinch-to-zoom, and multi-touch gestures into precise pointer events required by the FigCraft canvas interface.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-indigo-400 mt-1"></i>
                                <span><strong>Scoped Storage Integration:</strong> Adapts local project import/export functionality to adhere to modern Android scoped storage and SAF (Storage Access Framework) standards.</span>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="flex gap-4">
                    <div class="flex-shrink-0 w-8 h-8 rounded-full bg-indigo-600/20 border border-indigo-500/30 flex items-center justify-center text-indigo-400 font-bold text-sm">3</div>
                    <div>
                        <h3 class="text-lg font-semibold text-white mb-1">Build Pipeline</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">Compiled using Gradle with custom ProGuard rules to strip unnecessary web polyfills and optimize the APK binary footprint.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Attribution Section -->
        <section class="bg-slate-800/50 border border-slate-800 rounded-2xl p-8 backdrop-blur-sm">
            <div class="flex items-center gap-3 mb-6">
                <div class="p-3 bg-indigo-500/10 text-indigo-400 rounded-xl">
                    <i class="fa-solid fa-heart text-xl"></i>
                </div>
                <h2 class="text-2xl font-bold text-white">Attribution & Original Source</h2>
            </div>
            <p class="text-slate-300 mb-4 leading-relaxed">
                This project would not be possible without the incredible work done by the original creators of FigCraft.
            </p>
            <ul class="space-y-3 text-slate-300">
                <li class="flex items-center gap-3">
                    <i class="fa-solid fa-code-branch text-indigo-400"></i>
                    <span><strong>Original Upstream Project:</strong> <a href="https://github.com/" target="_blank" class="text-indigo-400 hover:underline">FigCraft Original Repository</a> (Refer to the source repository for upstream issues, licensing details, and core web documentation).</span>
                </li>
                <li class="flex items-center gap-3">
                    <i class="fa-solid fa-scale-balanced text-indigo-400"></i>
                    <span><strong>License:</strong> Licensed under the terms specified in the original upstream repository.</span>
                </li>
            </ul>
        </section>

        <!-- Installation Section -->
        <section id="installation" class="bg-slate-800/50 border border-slate-800 rounded-2xl p-8 backdrop-blur-sm">
            <div class="flex items-center gap-3 mb-6">
                <div class="p-3 bg-indigo-500/10 text-indigo-400 rounded-xl">
                    <i class="fa-solid fa-mobile-screen-button text-xl"></i>
                </div>
                <h2 class="text-2xl font-bold text-white">Installation Guide</h2>
            </div>
            <ol class="list-decimal list-inside space-y-3 text-slate-300 leading-relaxed">
                <li>Head over to the <a href="#" class="text-indigo-400 hover:underline font-medium">Releases</a> tab of this repository.</li>
                <li>Download the latest <code class="bg-slate-900 px-2 py-1 rounded text-indigo-300 text-sm font-mono">FigCraft-vX.X.X.apk</code> file.</li>
                <li>Enable <strong>Install from Unknown Sources</strong> in your Android device settings if prompted.</li>
                <li>Install the APK and launch FigCraft on your mobile device!</li>
            </ol>
        </section>

        <!-- Build from Source Section -->
        <section class="bg-slate-800/50 border border-slate-800 rounded-2xl p-8 backdrop-blur-sm">
            <div class="flex items-center gap-3 mb-6">
                <div class="p-3 bg-indigo-500/10 text-indigo-400 rounded-xl">
                    <i class="fa-solid fa-terminal text-xl"></i>
                </div>
                <h2 class="text-2xl font-bold text-white">Building from Source</h2>
            </div>
            <p class="text-slate-300 mb-4">If you wish to compile the Android wrapper yourself, run the following commands:</p>
            <div class="bg-slate-950 rounded-xl p-4 border border-slate-800 font-mono text-sm text-slate-300 overflow-x-auto">
                <pre><code>git clone https://github.com/your-username/FigCraft-Android.git
cd FigCraft-Android
./gradlew assembleDebug</code></pre>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-800 py-8 text-center text-slate-500 text-sm">
        <p>Maintained with ❤️ for the mobile creator community.</p>
    </footer>

</body>
</html>

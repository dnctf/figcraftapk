<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FigCraft Android APK Release</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #e2e8f0;
            --text-muted: #94a3b8;
            --accent-color: #38bdf8;
            --accent-hover: #0ea5e9;
            --border-color: #334155;
            --code-bg: #090d16;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 850px;
            margin: 0 auto;
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 2.5rem;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.3);
        }

        header {
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 1.5rem;
            margin-bottom: 2rem;
            text-align: center;
        }

        h1 {
            font-size: 2.25rem;
            color: #f8fafc;
            margin-bottom: 0.5rem;
        }

        .badge {
            display: inline-block;
            background-color: rgba(56, 189, 248, 0.1);
            color: var(--accent-color);
            border: 1px solid rgba(56, 189, 248, 0.2);
            padding: 0.25rem 0.75rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            font-weight: 600;
            margin-top: 0.5rem;
        }

        h2 {
            font-size: 1.5rem;
            color: #f8fafc;
            margin-top: 2rem;
            margin-bottom: 1rem;
            padding-bottom: 0.3rem;
            border-bottom: 1px solid var(--border-color);
        }

        h3 {
            font-size: 1.15rem;
            color: #cbd5e1;
            margin-top: 1.25rem;
            margin-bottom: 0.5rem;
        }

        p, ul {
            margin-bottom: 1rem;
            color: var(--text-muted);
        }

        ul {
            padding-left: 1.5rem;
        }

        li {
            margin-bottom: 0.5rem;
        }

        a {
            color: var(--accent-color);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
            color: var(--accent-hover);
        }

        .btn-container {
            margin: 1.5rem 0;
            text-align: center;
        }

        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: #0f172a;
            font-weight: 700;
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            transition: background-color 0.2s, transform 0.1s;
            text-decoration: none;
        }

        .btn:hover {
            background-color: var(--accent-hover);
            transform: translateY(-2px);
            text-decoration: none;
            color: #0f172a;
        }

        code {
            font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
            background-color: var(--code-bg);
            color: #e2e8f0;
            padding: 0.2rem 0.4rem;
            border-radius: 4px;
            font-size: 0.9em;
            border: 1px solid var(--border-color);
        }

        pre {
            background-color: var(--code-bg);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 1rem;
            overflow-x: auto;
            margin-bottom: 1.5rem;
        }

        pre code {
            background-color: transparent;
            border: none;
            padding: 0;
        }

        footer {
            margin-top: 3rem;
            border-top: 1px solid var(--border-color);
            padding-top: 1.5rem;
            text-align: center;
            font-size: 0.875rem;
            color: var(--text-muted);
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>FigCraft Android APK</h1>
            <p>Porting seluler dan rilis build mandiri untuk platform Android</p>
            <span class="badge">v1.0.0-release</span>
        </header>

        <section>
            <h2>Tentang Proyek Ini</h2>
            <p>Repositori ini mendedikasikan build porting dan rilis file APK Android untuk aplikasi <strong>FigCraft</strong>. Proyek ini diadaptasi dan dioptimalkan agar dapat berjalan mulus pada ekosistem perangkat seluler, termasuk tablet dan perangkat sentuh lainnya.</p>
            
            <div class="btn-container">
                <a href="#" class="btn">Unduh APK Terbaru</a>
            </div>
        </section>

        <section>
            <h2>Atribusi & Sumber Asli</h2>
            <p>Proyek ini dibangun di atas fondasi kode sumber terbuka dari repositori hulu (upstream). Kami menjunjung tinggi apresiasi kepada para pengembang original atas kontribusi luar biasa mereka pada proyek utama.</p>
            <ul>
                <li><strong>Repositori Hulu:</strong> <a href="https://github.com/org/figcraft" target="_blank">github.com/org/figcraft</a></li>
                <li><strong>Lisensi:</strong> Mengikuti ketentuan lisensi dari repositori asli.</li>
            </ul>
        </section>

        <section>
            <h2>Metodologi Porting & Penyesuaian</h2>
            <p>Proses adaptasi dan kompilasi APK ini melibatkan beberapa tahapan optimasi khusus:</p>
            <ul>
                <li><strong>Penyesuaian Antarmuka Sentuh:</strong> Mengonfigurasi ulang elemen interaktif agar responsif terhadap navigasi sentuh layar perangkat seluler.</li>
                <li><strong>Manajemen Memori:</strong> Mengoptimalkan batas alokasi heap dan pembuangan sampah memori agar stabil di berbagai spesifikasi hardware Android.</li>
                <li><strong>Build Pipeline:</strong> Menggunakan skrip otomatisasi untuk kompilasi silang (cross-compilation) langsung dari kode sumber terbaru.</li>
            </ul>
        </section>

        <section>
            <h2>Panduan Instalasi Cepat</h2>
            <p>Pastikan perangkat Anda mengizinkan instalasi dari sumber tidak dikenal sebelum memasang file APK.</p>
            <pre><code># Langkah verifikasi checksum file APK (opsional)
sha256sum FigCraft-v1.0.0.apk</code></pre>
        </section>

        <footer>
            <p>&copy; 2026 FigCraft Android Porting Project. Dibuat dengan format yang bersih dan responsif.</p>
        </footer>
    </div>

</body>
</html>

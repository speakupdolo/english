<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English Resources - SpeakUpDolo</title>
    <!-- Tailwind CSS CDN para estilos limpios y modernos -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 min-h-screen flex flex-col justify-between antialiased p-4 sm:p-6 lg:p-8">

    <main class="max-w-3xl mx-auto w-full space-y-8 my-auto">
        
        <!-- Cabecera Limpia y Profesional -->
        <header class="text-center space-y-2">
            <span class="inline-block bg-indigo-100 text-indigo-700 text-xs font-semibold px-3 py-1 rounded-full uppercase tracking-wider">GitHub Pages Hub</span>
            <h1 class="text-3xl sm:text-4xl font-bold text-slate-900 tracking-tight">Recursos de Inglés</h1>
            <p class="text-slate-600 max-w-md mx-auto text-sm sm:text-base">Selecciona cualquiera de las actividades interactivas para acceder al contenido.</p>
        </header>

        <!-- SECCIÓN DE ENLACES MAIN -->
        <!-- NOTA DE MANTENIMIENTO:
             Para agregar más botones de forma estática en HTML sin tocar JavaScript, 
             solo copia un bloque <a> dentro del siguiente contenedor: -->
        <section class="grid gap-3 sm:gap-4 sm:grid-cols-1" id="links-container">
            
            <!-- Botón 1: Números -->
            <a href="https://speakupdolo.github.io/english/number.html" 
               target="_blank" 
               rel="noopener noreferrer" 
               class="group flex items-center justify-between p-4 bg-white border border-slate-200 rounded-xl shadow-sm hover:shadow-md hover:border-indigo-500 hover:text-indigo-600 transition-all duration-200">
                <div class="flex items-center space-x-3">
                    <span class="text-2xl bg-indigo-50 p-2 rounded-lg group-hover:bg-indigo-100 transition-colors">🔢</span>
                    <span class="font-semibold text-slate-800 group-hover:text-indigo-600 text-base sm:text-lg">Números</span>
                </div>
                <div class="flex items-center space-x-1 text-slate-400 group-hover:text-indigo-600 font-medium text-sm">
                    <span>Abrir</span>
                    <svg class="w-5 h-5 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                    </svg>
                </div>
            </a>

            <!-- Botón 2: Calendario y Rutinas -->
            <a href="https://speakupdolo.github.io/english/calendar_routine.html" 
               target="_blank" 
               rel="noopener noreferrer" 
               class="group flex items-center justify-between p-4 bg-white border border-slate-200 rounded-xl shadow-sm hover:shadow-md hover:border-indigo-500 hover:text-indigo-600 transition-all duration-200">
                <div class="flex items-center space-x-3">
                    <span class="text-2xl bg-indigo-50 p-2 rounded-lg group-hover:bg-indigo-100 transition-colors">📅</span>
                    <span class="font-semibold text-slate-800 group-hover:text-indigo-600 text-base sm:text-lg">Calendario y Rutinas</span>
                </div>
                <div class="flex items-center space-x-1 text-slate-400 group-hover:text-indigo-600 font-medium text-sm">
                    <span>Abrir</span>
                    <svg class="w-5 h-5 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                    </svg>
                </div>
            </a>

            <!-- Botón 3: Juego 4 Años -->
            <a href="https://speakupdolo.github.io/english/game4year.html" 
               target="_blank" 
               rel="noopener noreferrer" 
               class="group flex items-center justify-between p-4 bg-white border border-slate-200 rounded-xl shadow-sm hover:shadow-md hover:border-indigo-500 hover:text-indigo-600 transition-all duration-200">
                <div class="flex items-center space-x-3">
                    <span class="text-2xl bg-indigo-50 p-2 rounded-lg group-hover:bg-indigo-100 transition-colors">🎮</span>
                    <span class="font-semibold text-slate-800 group-hover:text-indigo-600 text-base sm:text-lg">Juego 4 Años</span>
                </div>
                <div class="flex items-center space-x-1 text-slate-400 group-hover:text-indigo-600 font-medium text-sm">
                    <span>Abrir</span>
                    <svg class="w-5 h-5 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                    </svg>
                </div>
            </a>

            <!-- NUEVO BOTÓN (PLANTILLA PARA DUPLICAR):
            <a href="URL_AQUI" target="_blank" rel="noopener noreferrer" class="group flex items-center justify-between p-4 bg-white border border-slate-200 rounded-xl shadow-sm hover:shadow-md hover:border-indigo-500 hover:text-indigo-600 transition-all duration-200">
                <div class="flex items-center space-x-3">
                    <span class="text-2xl bg-indigo-50 p-2 rounded-lg">ICONO</span>
                    <span class="font-semibold text-slate-800 group-hover:text-indigo-600 text-base sm:text-lg">TITULO</span>
                </div>
                <div class="flex items-center space-x-1 text-slate-400 group-hover:text-indigo-600 font-medium text-sm">
                    <span>Abrir</span>
                    <svg class="w-5 h-5 transform group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                </div>
            </a>
            -->

        </section>

        <!-- SECCIÓN PARA EXPONDER CÓDIGO README.MD -->
        <section class="mt-12 border-t border-slate-200 pt-8">
            <div class="bg-slate-900 rounded-xl p-5 text-slate-100 shadow-xl space-y-4">
                <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-800 pb-3">
                    <div>
                        <h2 class="text-base font-semibold text-white">Código listo para README.md</h2>
                        <p class="text-xs text-slate-400">Copia y pega directamente en tu README para mostrar botones limpios en GitHub.</p>
                    </div>
                    <button id="copy-btn" onclick="copyReadmeCode()" class="bg-indigo-600 hover:bg-indigo-500 text-white text-xs font-semibold px-3 py-2 rounded-lg transition-colors flex items-center space-x-1">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"></path>
                        </svg>
                        <span id="copy-text">Copiar Código Markdown</span>
                    </button>
                </div>

                <pre class="bg-slate-950 p-4 rounded-lg text-xs font-mono text-indigo-300 overflow-x-auto whitespace-pre-wrap leading-relaxed border border-slate-800/80" id="readme-code">
### 🚀 Recursos Interactivos de Inglés

[![Números](https://img.shields.io/badge/🔢_Números-4F46E5?style=for-the-badge&logoColor=white)](https://speakupdolo.github.io/english/number.html)
[![Calendario y Rutinas](https://img.shields.io/badge/📅_Calendario_%26_Rutinas-0EA5E9?style=for-the-badge&logoColor=white)](https://speakupdolo.github.io/english/calendar_routine.html)
[![Juego 4 Años](https://img.shields.io/badge/🎮_Juego_4_Años-10B981?style=for-the-badge&logoColor=white)](https://speakupdolo.github.io/english/game4year.html)

---
*Alternativa con HTML (Botones limpios centrados):*

&lt;p align="center"&gt;
  &lt;a href="https://speakupdolo.github.io/english/number.html" target="_blank"&gt;
    &lt;img src="https://img.shields.io/badge/🔢_Números-4F46E5?style=for-the-badge" alt="Números"/&gt;
  &lt;/a&gt;
  &lt;a href="https://speakupdolo.github.io/english/calendar_routine.html" target="_blank"&gt;
    &lt;img src="https://img.shields.io/badge/📅_Calendario_y_Rutinas-0EA5E9?style=for-the-badge" alt="Calendario"/&gt;
  &lt;/a&gt;
  &lt;a href="https://speakupdolo.github.io/english/game4year.html" target="_blank"&gt;
    &lt;img src="https://img.shields.io/badge/🎮_Juego_4_Años-10B981?style=for-the-badge" alt="Juego 4 Años"/&gt;
  &lt;/a&gt;
&lt;/p&gt;</pre>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="text-center text-xs text-slate-400 py-6 border-t border-slate-200 mt-12">
        <p>SpeakUpDolo &bull; GitHub Pages Hub</p>
    </footer>

    <script>
        // Función limpia para copiar el texto del README
        function copyReadmeCode() {
            const codeText = document.getElementById('readme-code').innerText;
            
            // Textarea temporal para copiar asegurando compatibilidad
            const tempTextArea = document.createElement('textarea');
            tempTextArea.value = codeText;
            document.body.appendChild(tempTextArea);
            tempTextArea.select();
            document.execCommand('copy');
            document.body.removeChild(tempTextArea);

            // Feedback visual en el botón
            const copyBtnText = document.getElementById('copy-text');
            const originalText = copyBtnText.innerText;
            copyBtnText.innerText = '¡Copiado al portapapeles!';
            
            setTimeout(() => {
                copyBtnText.innerText = originalText;
            }, 2000);
        }
    </script>
</body>
</html>

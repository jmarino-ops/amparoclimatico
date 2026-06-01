<!DOCTYPE html>
<html lang="es-ES">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amparo Climático - Plataforma Legal Design</title>

    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <script src="https://unpkg.com/lucide@latest"></script>

    <style>
        :root {
            --azul-sillar: #1e3a8a;
            --terracota: #b45309;
        }

        .bg-azul-sillar {
            background-color: var(--azul-sillar);
        }

        .text-azul-sillar {
            color: var(--azul-sillar);
        }

        .bg-terracota {
            background-color: var(--terracota);
        }

        .border-terracota {
            border-color: var(--terracota);
        }

        .text-terracota {
            color: var(--terracota);
        }

        /* Efecto suave para scroll */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>

<body class="bg-gray-50 text-gray-800 font-sans min-h-screen pb-12">

    <header class="bg-azul-sillar text-white shadow-md sticky top-0 z-40">
        <div class="max-w-7xl mx-auto px-4 py-4 flex flex-col sm:flex-row justify-between items-center gap-4">
            <div class="flex items-center gap-3">
                <div class="p-1">
                    <img src="imagenes/logo (2).png" alt="Logo Amparo Climático" class="w-16 h-16 object-contain">
                </div>
                <div>
                    <h1 class="text-8x1 font-bold tracking-tight">
                        AMPARO CLIMÁTICO
                    </h1>
                    <p class="text-xs text-blue-200">Legal Design aplicado a la Justicia Climática en Arequipa</p>
                </div>
            </div>
            <nav class="flex flex-wrap justify-center gap-2 text-sm">
                <a href="#metodologia" class="px-3 py-1.5 rounded-md hover:bg-white/10 transition">Metodología</a>
                <a href="#perfiles" class="px-3 py-1.5 rounded-md hover:bg-white/10 transition">Usuarios</a>
                <a href="#problema" class="px-3 py-1.5 rounded-md hover:bg-white/10 transition">El Desafío</a>
                <a href="#prototipo"
                    class="px-3 py-1.5 rounded-md bg-amber-500 text-slate-950 font-bold hover:bg-amber-400 transition shadow">Ver
                    SOS Digital</a>
                <a href="#comparativa" class="px-3 py-1.5 rounded-md hover:bg-white/10 transition">Análisis Global</a>
            </nav>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 mt-8 space-y-12">

        <section
            class="bg-white rounded-2xl p-8 border border-gray-200 shadow-sm grid md:grid-cols-3 gap-8 items-center">
            <div class="md:col-span-2 space-y-4">
                <span
                    class="bg-amber-100 text-amber-800 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">Propósito
                    del Proyecto</span>
                <h2 class="text-3xl font-black text-slate-900 tracking-tight">Democratizar el Derecho: El Contrato como
                    Escudo, no como Laberinto</h2>
                <p class="text-gray-600 leading-relaxed">
                    Tomamos la complejidad abstracta del Derecho Civil contractual peruano y la transformamos en un
                    protocolo visual accionable directamente desde el celular para proteger a quienes sostienen la
                    economía regional ante la crudeza del clima en Arequipa.
                </p>
            </div>
            <div class="bg-amber-50 border border-amber-200 rounded-xl p-5 space-y-3">
                <h3 class="font-bold text-amber-900 flex items-center gap-2 text-sm uppercase tracking-wide">
                    <i data-lucide="lightbulb" class="w-4 h-4 text-amber-600"></i> Origen de la Inspiración
                </h3>
                <p class="text-xs text-amber-800 leading-relaxed">
                    <strong>La geografía implacable:</strong> Derrumbes en la Panamericana y heladas en Caylloma que
                    destruyen mercancías. <br><br>
                    <strong>Injusticia del lenguaje técnico:</strong> Las cláusulas tradicionales ocultan herramientas
                    de protección como la 'Fuerza Mayor' bajo tecnicismos abogadescos ilegibles en plena crisis.
                </p>
            </div>
        </section>

        <section id="metodologia" class="space-y-6">
            <div class="border-l-4 border-azul-sillar pl-3">
                <h2 class="text-2xl font-bold text-slate-900">1. Marco Científico y Académico</h2>
                <p class="text-sm text-gray-500">Alineación con los estándares globales del Stanford Legal Design Lab
                </p>
            </div>

            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm space-y-4">
                    <div class="flex items-center gap-3 text-azul-sillar font-bold text-lg">
                        <i data-lucide="layers" class="w-6 h-6"></i>
                        <h3>Tipología de Diseño Legal</h3>
                    </div>
                    <ul class="space-y-3 text-sm text-gray-600">
                        <li class="p-3 bg-slate-50 rounded-lg">
                            <strong class="text-slate-900 block mb-1">Diseño de Información Legal (Legal Information
                                Design)</strong>
                            <span>Traduce textos normativos oscuros (Arts. 1315, 1316 y 1431 del C.C.) a interfaces
                                legibles, organizadas y esquematizadas para el ciudadano común.</span>
                        </li>
                        <li class="p-3 bg-slate-50 rounded-lg">
                            <strong class="text-slate-900 block mb-1">Diseño de Producto/Tecnología Legal (Legal
                                Product/Tech Design)</strong>
                            <span>Crea herramientas digitales funcionales e interactivas (automatización de alertas vía
                                WhatsApp) centradas estrictamente en la experiencia del usuario final.</span>
                        </li>
                    </ul>
                </div>

                <div class="bg-white p-6 rounded-xl border border-gray-200 shadow-sm space-y-4">
                    <div class="flex items-center gap-3 text-terracota font-bold text-lg">
                        <i data-lucide="search" class="w-6 h-6"></i>
                        <h3>Línea de Investigación Científica</h3>
                    </div>
                    <p class="text-sm font-semibold text-gray-700 bg-amber-50 p-2 rounded border border-amber-200">
                        Macro-misión: Acceso a la Justicia y Empoderamiento Legal (Access to Justice & Legal
                        Empowerment)
                    </p>
                    <ul class="space-y-3 text-sm text-gray-600">
                        <li class="p-3 bg-slate-50 rounded-lg">
                            <strong class="text-slate-900 block mb-1">Navegación del Sistema y Autorepresentación
                                (Self-Help)</strong>
                            <span>Investiga cómo los recursos gráficos permiten que un ciudadano active mecanismos de
                                defense oportunos en la primera fase del conflicto sin requerir un abogado
                                transcriptor.</span>
                        </li>
                        <li class="p-3 bg-slate-50 rounded-lg">
                            <strong class="text-slate-900 block mb-1">Diseño de Contratos Claros y Prevención de
                                Disputas</strong>
                            <span>Estructura acuerdos comerciales transparentes desde el inicio, minimizando la
                                judicialización y resolviendo la crisis de mutuo acuerdo de forma proactiva.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="perfiles" class="space-y-6">
            <div class="border-l-4 border-terracota pl-3">
                <h2 class="text-2xl font-bold text-slate-900">2. Investigación de Usuarios e Inclusión Regional</h2>
                <p class="text-sm text-gray-500">Modelos de empatía construidos para perfiles críticos expuestos a
                    riesgos climáticos en Arequipa</p>
            </div>

            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-white border-t-4 border-azul-sillar rounded-xl p-6 shadow-sm space-y-4">
                    <div class="flex items-center justify-between">
                        <h3 class="text-lg font-bold text-slate-900 flex items-center gap-2">
                            <i data-lucide="truck" class="w-5 h-5 text-azul-sillar"></i> Perfil 1: El Transportista de
                            Carga Pesada
                        </h3>
                        <span class="bg-blue-100 text-azul-sillar text-[10px] font-bold px-2 py-0.5 rounded">Logística
                            de Rutas</span>
                    </div>
                    <div class="space-y-2 text-sm text-gray-600">
                        <p><strong>Rutas Críticas:</strong> <span>Panamericana Sur (Vítor, El Fiscal, Chala) o Variante
                                hacia Yura/Puno.</span></p>
                        <p><strong class="text-slate-900">Mercancía en Riesgo:</strong> <span>Perecibles de alta demanda
                                (cebolla de Camaná, ajo de Tambo, lácteos de Majes).</span></p>
                        <p class="bg-gray-50 p-3 rounded border border-gray-100 italic">
                            <strong>Necesidad Real:</strong> Saber qué hacer legalmente en el minuto exacto en que un
                            derrumbe bloquea la vía y la carga corre el riesgo inminente de pudrirse. Exige respuestas
                            directas offline en su pantalla celular.
                        </p>
                    </div>
                </div>

                <div class="bg-white border-t-4 border-terracota rounded-xl p-6 shadow-sm space-y-4">
                    <div class="flex items-center justify-between">
                        <h3 class="text-lg font-bold text-slate-900 flex items-center gap-2">
                            <i data-lucide="sprout" class="w-5 h-5 text-terracota"></i> Perfil 2: El Agricultor /
                            Productor Alpaquero
                        </h3>
                        <span class="bg-amber-100 text-terracota text-[10px] font-bold px-2 py-0.5 rounded">Zonas
                            Vulnerables</span>
                    </div>
                    <div class="space-y-2 text-sm text-gray-600">
                        <p><strong>Ubicación Estratégica:</strong> <span>Valles regulados (Majes, La Joya) o áreas
                                altoandinas (Caylloma, Imata, Condesuyos).</span></p>
                        <p><strong class="text-slate-900">Mercancía en Riesgo:</strong> <span>Cosechas agrarias de ciclo
                                corto o fibra de alpaca fina.</span></p>
                        <p class="bg-gray-50 p-3 rounded border border-gray-100 italic">
                            <strong>Necesidad Real:</strong> Entender si el acopiador corporativo tiene facultad de
                            demandarlo o retenerle penalidades cuando una helada extrema aniquila su producción tras
                            haber firmado un contrato rígido de suministro masivo.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <section id="problema" class="bg-red-50 border border-red-200 rounded-2xl p-6 md:p-8 space-y-6">
            <div class="flex items-center gap-3 text-red-800">
                <i data-lucide="alert-triangle" class="w-8 h-8 flex-shrink-0"></i>
                <div>
                    <h2 class="text-xl font-bold tracking-tight">3. El Diagnóstico del Dolor: Opacidad en los Contratos
                    </h2>
                    <p class="text-xs text-red-700">Cómo el lenguaje técnico genera indefensión real ante el cambio
                        climático</p>
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-6 items-stretch">
                <div class="bg-white p-5 rounded-xl border border-red-100 flex flex-col justify-between">
                    <div>
                        <span class="text-[10px] font-bold uppercase tracking-wider text-red-600 block mb-1">Cláusula
                            Tradicional Ininteligible</span>
                        <p
                            class="text-xs text-gray-500 font-mono bg-gray-50 p-3 rounded border border-gray-200 leading-relaxed">
                            "Cláusula Novena: Las partes acuerdan que la responsabilidad civil por inejecución se rige
                            estrictamente por el Art. 1315 del C.C. El deudor deberá acreditar fehacientemente la
                            configuración causal de fuerza mayor mediante instrumental idóneo y fidedigno dentro del
                            plazo de caducidad perentorio bajo apercibimiento de ejecutarse de pleno derecho las
                            penalidades pactadas..."
                        </p>
                    </div>
                    <p class="text-xs text-red-600 font-medium mt-3">
                        ⚠️ Resultado Práctico: El transportista estancado en Uchumayo o el agricultor en Caylloma no
                        comprenden el texto, experimentan temor injustificado y asumen coactivamente pérdidas
                        financieras devastadoras.
                    </p>
                </div>

                <div class="bg-white p-5 rounded-xl border border-red-100 flex flex-col justify-between">
                    <div>
                        <span class="text-[10px] font-bold uppercase tracking-wider text-green-600 block mb-1">La
                            Transformación del Enfoque</span>
                        <p class="text-sm text-gray-700 leading-relaxed">
                            El Legal Design elimina la asimetría informativa. La solución no reduce el rigor jurídico;
                            modifica sustancialmente el canal y la semántica comunicativa para centrarse en el cliente
                            en momentos de máxima urgencia emocional.
                        </p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-gray-100 grid grid-cols-3 gap-2 text-center text-xs">
                        <div class="p-2 bg-gray-50 rounded"><span class="block font-bold text-red-700">0%</span> <span
                                class="text-[10px] text-gray-400">Comprensión Inicial</span></div>
                        <div class="p-2 bg-gray-50 rounded"><span class="block font-bold text-blue-700">100%</span>
                            <span class="text-[10px] text-gray-400">Base en Código Civil</span>
                        </div>
                        <div class="p-2 bg-gray-50 rounded"><span class="block font-bold text-green-700">&lt; 2
                                min</span> <span class="text-[10px] text-gray-400">Tiempo Respuesta</span></div>
                    </div>
                </div>
            </div>
        </section>

        <section id="prototipo" class="space-y-6">
            <div class="border-l-4 border-amber-500 pl-3">
                <span
                    class="bg-amber-500 text-slate-950 font-black text-[10px] uppercase tracking-widest px-2 py-0.5 rounded">Entregable
                    Funcional</span>
                <h2 class="text-2xl font-bold text-slate-900">4. Prototipo Proactivo: Cartilla SOS Contractual - Clima
                    Arequipa</h2>
                <p class="text-sm text-gray-500">Secuencia de imágenes del marco contractual mapeadas por artículo legal
                </p>
            </div>

            <div
                class="max-w-md mx-auto bg-white border-8 border-slate-900 rounded-[3rem] shadow-2xl overflow-hidden relative my-4">
                <div class="bg-slate-900 text-white px-6 py-2 flex justify-between items-center text-[11px] font-mono">
                    <span>12:45 ☀️ (Arequipa)</span>
                    <div class="flex items-center gap-1">
                        <i data-lucide="wifi" class="w-3 h-3"></i>
                        <i data-lucide="battery" class="w-4 h-4"></i>
                    </div>
                </div>

                <div class="bg-azul-sillar text-white p-5 text-center space-y-1">
                    <h3 class="text-sm font-black tracking-widest text-amber-400">CARTILLA SOS CONTRACTUAL</h3>
                    <p class="text-lg font-bold">¡Emergencia Climática!</p>
                    <p class="text-[11px] text-blue-200">Guía interactiva paso a paso corregida</p>
                </div>

                <div class="p-4 space-y-6 max-h-[550px] overflow-y-auto bg-slate-50">

                    <div class="bg-white rounded-xl p-3 shadow-xs border border-gray-200 space-y-2 text-center">
                        <span
                            class="bg-blue-100 text-blue-800 text-[9px] font-bold px-2 py-0.5 rounded-full uppercase">Paso
                            1: Portada Inicial</span>
                        <div class="overflow-hidden rounded-lg bg-gray-100 border border-gray-200">
                            <img src="imagenes/logo (2).png" Portada de la Cartilla SOS Contractual"
                                class="w-full h-auto object-contain mx-auto block">
                        </div>
                        <p <div class="bg-white border-l-4 border-blue-600 rounded-xl p-3 shadow-xs space-y-2">
                        <div class="flex items-center gap-2 text-blue-900 font-bold text-xs">
                            <i data-lucide="shield" class="w-4 h-4 text-blue-600"></i>
                        </div>
                        <div class="overflow-hidden rounded-lg bg-gray-100 border border-gray-200">
                            <img src="imagenes/imagen 1.jpeg" alt="Artículo 1315 Caso Fortuito y Fuerza Mayor"
                                class="w-full h-auto object-contain mx-auto block">
                        </div>
                        <p class="text-[11px] text-gray-600">
                        </p>
                    </div>

                    <div class="bg-white border-l-4 border-sky-600 rounded-xl p-3 shadow-xs space-y-2">
                        <div class="flex items-center gap-2 text-sky-900 font-bold text-xs">
                            <i data-lucide="list-check" class="w-4 h-4 text-sky-600"></i>
                        </div>
                        <div class="overflow-hidden rounded-lg bg-gray-100 border border-gray-200">
                            <img src="imagenes/imagen 2.jpeg" alt="Los tres requisitos del artículo 1315"
                                class="w-full h-auto object-contain mx-auto block">
                        </div>
                        <p class="text-[11px] text-gray-600">
                        </p>
                    </div>

                    <div class="bg-white border-l-4 border-amber-600 rounded-xl p-3 shadow-xs space-y-2">
                        <div class="flex items-center gap-2 text-amber-950 font-bold text-xs">
                            <i data-lucide="scale-3d" class="w-4 h-4 text-amber-600"></i>
                        </div>
                        <div class="overflow-hidden rounded-lg bg-gray-100 border border-gray-200">
                            <img src="imagenes/imagen 3.jpeg" alt="Artículo 1431 Teoría del Riesgo"
                                class="w-full h-auto object-contain mx-auto block">
                        </div>
                        <p class="text-[11px] text-gray-600">
                        </p>
                    </div>

                    <div class="bg-white border-l-4 border-purple-600 rounded-xl p-3 shadow-xs space-y-2">
                        <div class="flex items-center gap-2 text-purple-900 font-bold text-xs">
                            <i data-lucide="heart-handshake" class="w-4 h-4 text-purple-600"></i>
                        </div>
                        <div class="overflow-hidden rounded-lg bg-gray-100 border border-gray-200">
                            <img src="imagenes/imagen 4.jpeg" alt="Artículo 1362 Principio de Buena Fe"
                                class="w-full h-auto object-contain mx-auto block">
                        </div>
                        <p class="text-[11px] text-gray-600">
                        </p>
                    </div>

                    <div class="bg-white border-l-4 border-emerald-600 rounded-xl p-3 shadow-xs space-y-2">
                        <div class="flex items-center gap-2 text-emerald-950 font-bold text-xs">
                            <i data-lucide="check-square" class="w-4 h-4 text-emerald-600"></i>
                        </div>
                        <div class="overflow-hidden rounded-lg bg-gray-100 border border-gray-200">
                            <img src="imagenes/imagen 5.jpeg" alt="Plan de Acción SOS Final"
                                class="w-full h-auto object-contain mx-auto block">
                        </div>
                        <p class="text-[11px] text-gray-600">
                        </p>

                        <button onclick="copiarMensaje()"
                            class="w-full mt-2 bg-green-600 hover:bg-green-700 text-white text-xs font-bold py-2 px-3 rounded-lg flex items-center justify-center gap-1.5 shadow transition-all cursor-pointer">
                            <i data-lucide="send" class="w-3 h-3"></i> Copiar Plantilla de WhatsApp
                        </button>
                    </div>
                    <div class="bg-white border-l-4 border-emerald-600 rounded-xl p-3 shadow-xs space-y-2">
                        <div class="flex items-center gap-2 text-emerald-950 font-bold text-xs">
                            <i data-lucide="check-square" class="w-4 h-4 text-emerald-600"></i>
                        </div>
                        <div class="overflow-hidden rounded-lg bg-gray-100 border border-gray-200">
                            <img src="imagenes/imagen 6.jpeg" alt="Plan de Acción SOS Final"
                                class="w-full h-auto object-contain mx-auto block">
                        </div>
                        <p class="text-[11px] text-gray-600">
                        </p>

                        <button onclick="copiarMensaje()"
                            class="w-full mt-2 bg-green-600 hover:bg-green-700 text-white text-xs font-bold py-2 px-3 rounded-lg flex items-center justify-center gap-1.5 shadow transition-all cursor-pointer">
                            <i data-lucide="send" class="w-3 h-3"></i> Copiar Plantilla de WhatsApp
                        </button>
                    </div>

                </div>

                <div class="bg-slate-900 p-3 flex justify-center">
                    <div class="w-24 h-1 bg-white/40 rounded-full"></div>
                </div>
            </div>
            <p class="text-center text-xs text-gray-400 italic">La interfaz distribuye el conocimiento en módulos
                visuales perfectamente escaneables en situaciones de alta presión o baja conectividad.</p>
        </section>

        <section class="space-y-6">
            <div class="border-l-4 border-gray-700 pl-3">
                <h2 class="text-2xl font-bold text-slate-900">5. Evaluación de Impacto y Validation Metodológica</h2>
                <p class="text-sm text-gray-500">Las seis variables matrices del diseño aplicadas al proyecto</p>
            </div>

            <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="bg-white p-4 rounded-xl border border-gray-200 shadow-xs space-y-1">
                    <h4 class="font-bold text-sm text-slate-900 flex items-center gap-1.5"><i data-lucide="smile"
                            class="text-blue-600 w-4 h-4"></i> Usabilidad Operativa</h4>
                    <p class="text-xs text-gray-600">Acceso ultraligero que opera sin consumo de datos críticos,
                        resolviendo dudas contractuales en ruta.</p>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-200 shadow-xs space-y-1">
                    <h4 class="font-bold text-sm text-slate-900 flex items-center gap-1.5"><i data-lucide="gavel"
                            class="text-purple-600 w-4 h-4"></i> Justicia Procesal</h4>
                    <p class="text-xs text-gray-600">Garantiza al eslabón más débil de la cadena productiva la
                        convicción de que la norma lo ampara.</p>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-200 shadow-xs space-y-1">
                    <h4 class="font-bold text-sm text-slate-900 flex items-center gap-1.5"><i data-lucide="heart"
                            class="text-emerald-600 w-4 h-4"></i> Engagement</h4>
                    <p class="text-xs text-gray-600">Fomenta una cultura de prevención contractual proactiva antes del
                        surgimiento de catástrofes.</p>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-200 shadow-xs space-y-1">
                    <h4 class="font-bold text-sm text-slate-900 flex items-center gap-1.5"><i data-lucide="award"
                            class="text-amber-600 w-4 h-4"></i> Capacidad Legal</h4>
                    <p class="text-xs text-gray-600">Instruye eficazmente sobre la recopilación ordenada de pruebas
                        válidas para repeler litigios de mala fe.</p>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-200 shadow-xs space-y-1">
                    <h4 class="font-bold text-sm text-slate-900 flex items-center gap-1.5"><i data-lucide="check-circle"
                            class="text-indigo-600 w-4 h-4"></i> Resolución Efectiva</h4>
                    <p class="text-xs text-gray-600">Liquida la asimetría semántica impidiendo que se inicien procesos
                        judiciales desgastantes e innecesarios.</p>
                </div>
                <div class="bg-white p-4 rounded-xl border border-gray-200 shadow-xs space-y-1">
                    <h4 class="font-bold text-sm text-slate-900 flex items-center gap-1.5"><i
                            data-lucide="trending-down" class="text-red-600 w-4 h-4"></i> Carga Administrativa</h4>
                    <p class="text-xs text-gray-600">Evita sobrecostos en asesorías de emergencia y trámites repetitivos
                        ante desastres de dominio público.</p>
                </div>
            </div>
        </section>

        <section id="comparativa" class="space-y-6">
            <div class="border-l-4 border-azul-sillar pl-3">
                <h2 class="text-2xl font-bold text-slate-900">6. Benchmark e Innovación: Amparo Climático vs. Flood
                    Proof (EE.UU.)</h2>
                <p class="text-sm text-gray-500">Análisis comparativo frente al referente internacional de tecnología
                    legal ante crisis hídricas</p>
            </div>

            <div class="bg-white rounded-xl border border-gray-200 shadow-sm overflow-hidden">
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-sm border-collapse">
                        <thead>
                            <tr class="bg-slate-900 text-white text-xs uppercase tracking-wider">
                                <th class="p-4">Eje de Análisis</th>
                                <th class="p-4">Flood Proof (Ecosistema EE.UU.)</th>
                                <th class="p-4 bg-azul-sillar text-amber-400">Amparo Climático (Propuesta Local)</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-gray-200 text-xs text-gray-600">
                            <tr>
                                <td class="p-4 font-bold text-slate-900">Propósito Central</td>
                                <td class="p-4">Saneamiento y clarificación de títulos de propiedad para destrabar
                                    fondos de reconstrucción post-inundación de FEMA.</td>
                                <td class="p-4 bg-blue-50/50 text-slate-900 font-medium">Desactivación inmediata de
                                    penalidades contractuales comerciales por eventos de Fuerza Mayor y Caso Fortuito
                                    (Código Civil).</td>
                            </tr>
                            <tr>
                                <td class="p-4 font-bold text-slate-900">Arquitectura Técnica</td>
                                <td class="p-4">Plataforma integral automatizada y ecosistema app para triaje de daños y
                                    reclamos de seguros.</td>
                                <td class="p-4 bg-blue-50/50 text-slate-900 font-medium">Cartilla digital interactiva
                                    minimalista optimizada para mensajería instantánea y consumo rápido.</td>
                            </tr>
                            <tr>
                                <td class="p-4 font-bold text-slate-900">Vacío que Resuelve</td>
                                <td class="p-4">Centraliza servicios fragmentados de asistencia gubernamental
                                    estadounidense.</td>
                                <td class="p-4 bg-blue-50/50 text-slate-900 font-medium">Cubre el vacío de herramientas
                                    proactivas para el ciudadano, integrando datos contextuales de INDECI, SUTRAN y
                                    SENAMHI Arequipa.</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

    </main>
    <!-- Sección Misión y Visión -->
    <section id="mision-vision" class="mision-vision">
        <div class="container">
            <div class="border-l-4 border-azul-sillar pl-3">
                <h2 class="text-2xl font-bold text-slate-900">7. Nuestra misión y visión </h2>
                <p class="text-sm text-gray-500"></p>
            </div>


            <div class="cards">
                <div class="card">
                    <h3>🎯 Misión</h3>
                    <p>
                        Transformar el derecho complejo en un escudo visual y accesible para proteger el patrimonio de
                        los productores, agricultores y transportistas de Arequipa ante las emergencias climáticas.
                    </p>

                    <p>
                        Nos dedicamos a rediseñar los contratos e instrumentos legales tradicionales utilizando la
                        metodología de Legal Design. Traducimos la burocracia del Código Civil a herramientas digitales
                        e infografías de acción inmediata, garantizando que los motores económicos de nuestra región se
                        defiendan con éxito de penalidades injustas cuando el clima (huaicos, heladas o friajes) les
                        impide cumplir con sus obligaciones.
                    </p>
                </div>

                <div class="card">
                    <h3>🚀 Visión</h3>
                    <p>
                        Ser la plataforma líder en innovación jurídica, logrando que para el año 2030 ningún trabajador
                        de la tierra o de la ruta sufra pérdidas judiciales o financieras por pura desinformación
                        contractual o extracontractual.
                    </p>

                    <p>
                        Aspiramos a consolidar una cultura legal donde la claridad visual sea la norma y no la
                        excepción. Buscamos que las grandes empresas acopiadoras, transportistas y entidades judiciales
                        adopten de manera estandarizada nuestros anexos visuales, democratizando el acceso a la justicia
                        procesal y convirtiendo a Arequipa en el referente nacional de derecho preventivo y resiliente
                        frente al cambio climático.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <style>
        .mision-vision {
            padding: 80px 20px;
            background: #f5f9fc;
        }

        .mision-vision .container {
            max-width: 1200px;
            margin: auto;
        }


        .cards {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card {
            flex: 1;
            min-width: 320px;
            max-width: 550px;
            background: #ffffff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        .card h3 {
            color: #0d6efd;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }

        .card p {
            color: #444;
            line-height: 1.8;
            text-align: justify;
        }
    </style>
    <script>
        // Inicializar iconos decorativos Lucide
        lucide.createIcons();

        // Lógica del botón interactivo para simular el mensaje SOS de WhatsApp
        function copiarMensaje() {
            const mensajeSOS = "ALERTA LEGAL: Estimado deudor/acreedor, debido a factores climáticos severos oficialmente reportados en la región Arequipa, se ha configurado un evento insalvable de Fuerza Mayor (según el Art. 1315 del Código Civil). Adjunto evidencias gráficas del siniestro. El cumplimiento regular de la prestación queda temporalmente suspendido bajo el principio de buena fe.";

            navigator.clipboard.writeText(mensajeSOS).then(() => {
                alert("¡Plantilla de contingencia legal formal copiada al portapapeles! Lista para ser enviada por mensajería instantánea.");
            }).catch(err => {
                console.error("Error al copiar texto: ", err);
            });
        }
    </script>
    <div class="container">
        <div class="max-w-2xl mx-20">
            <div class="border-l-3 border-azul-sillar pl-2">
                <h2 class="text-2xl font-bold text-slate-900">
                </h2>
            </div>
        </div>
        <div class="max-w-4xl mx-auto bg-white rounded-3xl shadow-lg border border-gray-200 p-8">

            <div class="grid md:grid-cols-3 gap-4 text-center">

                <div class="px-4">
                    <img src="imagenes/persona 1.png"
                        class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-blue-200">

                    <h3 class="mt-4 text-xl font-bold">
                        ASESORAMIENTO LEGAL
                    </h3>

                    <p class="text-amber-600 font-semibold">

                    </p>

                    <p class="mt-3 text-sm text-gray-600">
                        Consulta con un abogado y ahorre hasta un 70% en comparación con los honorarios habituales
                    </p>
                </div>

                <!-- Persona 2 -->
                <div class="px-4">
                    <img src="imagenes/persona 2.png"
                        class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-blue-200">

                    <h3 class="mt-4 text-xl font-bold">
                        SERVICIOS PROFESIONALES
                    </h3>

                    <p class="text-amber-600 font-semibold">

                    </p>

                    <p class="mt-3 text-sm text-gray-600">

                    </p>
                </div>
                <!-- Persona 3 -->
                <div class="px-4">
                    <img src="imagenes/persona 3.png"
                        class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-blue-200">

                    <h3 class="mt-4 text-xl font-bold">
                        SOPORTE PERSONALIZADO
                    </h3>

                    <p class="text-amber-600 font-semibold">

                    </p>

                    <p class="mt-3 text-sm text-gray-600">
                        Obtenga ayuda de expertos legajes adaptada a sus necesidades
                    </p>
                </div>
            </div>

        </div>
    </div>

    </section>
    <section id="valores" class="my-12">

        <div class="max-w-2xl mx-20">
            <div class="border-l-4 border-azul-sillar pl-">
                <h2 class="text-2xl font-bold text-slate-900">
                    8. Valores Institucionales </h2>
            </div>
        </div>

        <div class="max-w-5xl mx-auto space-y-4">

            <!-- Valor 1 -->
            <details class="bg-white rounded-xl border border-gray-200 shadow-sm p-15">
                <summary class="font-bold text-lg text-azul-sillar cursor-pointer">
                    🌎 Empatía Territorial
                </summary>
                <p class="mt-4 text-gray-600 leading-relaxed">
                    Diseñamos con los pies en la tierra y las manos en el volante.
                    Nos ponemos en el lugar del camionero varado en Yura a mitad de la noche
                    o del alpaquero en Caylloma viendo su pasto congelado.
                    El dolor de nuestro usuario guía cada decisión gráfica y legal.
                </p>
            </details>

            <!-- Valor 2 -->
            <details class="bg-white rounded-xl border border-gray-200 shadow-sm p-4">
                <summary class="font-bold text-lg text-azul-sillar cursor-pointer">
                    📘 Claridad Radical (Legal Design)
                </summary>
                <p class="mt-4 text-gray-600 leading-relaxed">
                    Rechazamos el lenguaje denso y el secretismo burocrático.
                    Creamos herramientas que se entienden en menos de 2 minutos
                    por cualquier ciudadano, porque un derecho que no se comprende,
                    no es justicia.
                </p>
            </details>

            <!-- Valor 3 -->
            <details class="bg-white rounded-xl border border-gray-200 shadow-sm p-4">
                <summary class="font-bold text-lg text-azul-sillar cursor-pointer">
                    ⚖️ Equidad y Justicia Procesal
                </summary>
                <p class="mt-4 text-gray-600 leading-relaxed">
                    Creemos que la ley debe proteger con la misma fuerza al pequeño
                    productor independiente que a la corporación.
                    Nivelamos la balanza contractual a través de la información transparente.
                </p>
            </details>

            <!-- Valor 4 -->
            <details class="bg-white rounded-xl border border-gray-200 shadow-sm p-4">
                <summary class="font-bold text-lg text-azul-sillar cursor-pointer">
                    🤝 Buena Fe Preventiva
                </summary>
                <p class="mt-4 text-gray-600 leading-relaxed">
                    Promovemos la resolución inmediata de conflictos directamente entre las partes
                    en el momento del desastre. Evitamos que las familias gasten tiempo y dinero
                    en juicios largos o trámites innecesarios mediante alertas y plantillas automatizadas.
                </p>
            </details>

            <!-- Valor 5 -->
            <details class="bg-white rounded-xl border border-gray-200 shadow-sm p-4">
                <summary class="font-bold text-lg text-azul-sillar cursor-pointer">
                    🏔️ Identidad y Resiliencia Arequipeña
                </summary>
                <p class="mt-4 text-gray-600 leading-relaxed">
                    Nos inspiramos en la fuerza de nuestra región. Nuestra identidad visual,
                    basada en el azul sillar y el terracota, refleja el orgullo local y la
                    capacidad de sobreponerse a la adversidad climática con ingenio e innovación.
                </p>
            </details>

        </div>
        <!-- Sección Necesitas Ayuda -->
        <section class="py-12">
            <div class="max-w-md mx-auto bg-white rounded-3xl shadow-lg border border-gray-200 p-8 text-center">

                <!-- Título -->
                <h2 class="text-2xl font-bold text-slate-900 mb-6">
                    ¿Necesitas ayuda?
                </h2>

                <!-- Foto Circular -->
                <div class="flex justify-center mb-6">
                    <img src="imagenes/asesora.png" alt="Asesor Legal"
                        class="w-40 h-40 rounded-full object-cover border-4 border-blue-200 shadow-md">
                </div>

                <!-- Botón -->
                <div class="flex justify-center">
                    <a href="#"
                        class="bg-azul-sillar hover:bg-blue-900 text-white font-semibold px-8 py-3 rounded-full transition duration-300 shadow-md">
                        Contáctanos
                    </a>
                </div>

            </div>
        </section>
    </section>

<footer class="bg-slate-900 text-white mt-20">

    <div class="max-w-7xl mx-auto px-6 py-12">

        <div class="grid md:grid-cols-4 gap-10">

            <!-- Logo e información -->
            <div>
                <img src="imagenes/logo (2).png"
                    alt="Amparo Climático"
                    class="w-20 mb-4">

                <h3 class="text-xl font-bold text-amber-400">
                    AMPARO CLIMÁTICO
                </h3>

                <p class="text-gray-300 text-sm mt-3 leading-relaxed">
                    Plataforma de Legal Design orientada a proteger a productores,
                    agricultores y transportistas de Arequipa frente a emergencias
                    climáticas mediante herramientas jurídicas visuales y accesibles.
                </p>
            </div>

            <!-- Navegación -->
            <div>
                <h4 class="font-bold text-lg text-white mb-4">
                    Navegación
                </h4>

                <ul class="space-y-2 text-gray-300 text-sm">
                    <li><a href="#metodologia" class="hover:text-amber-400">Metodología</a></li>
                    <li><a href="#perfiles" class="hover:text-amber-400">Usuarios</a></li>
                    <li><a href="#problema" class="hover:text-amber-400">El Desafío</a></li>
                    <li><a href="#prototipo" class="hover:text-amber-400">Prototipo</a></li>
                    <li><a href="#comparativa" class="hover:text-amber-400">Benchmark</a></li>
                    <li><a href="#valores" class="hover:text-amber-400">Valores</a></li>
                </ul>
            </div>

            <!-- Contacto -->
            <div>
                <h4 class="font-bold text-lg text-white mb-4">
                    Contacto
                </h4>

                <ul class="space-y-3 text-gray-300 text-sm">
                    <li class="flex items-center gap-2">
                        📍 Arequipa - Perú
                    </li>

                    <li class="flex items-center gap-2">
                        📧 contacto@amparoclimatico.pe
                    </li>

                    <li class="flex items-center gap-2">
                        📱 +51 999 999 999
                    </li>

                    <li class="flex items-center gap-2">
                        🌐 www.amparoclimatico.pe
                    </li>
                </ul>
            </div>

            <!-- Redes Sociales -->
            <div>
                <h4 class="font-bold text-lg text-white mb-4">
                    Síguenos
                </h4>

                <div class="flex gap-4">

                    <a href="#"
                        class="bg-blue-600 hover:bg-blue-700 p-3 rounded-full transition">
                        <i data-lucide="facebook"></i>
                    </a>

                    <a href="#"
                        class="bg-pink-600 hover:bg-pink-700 p-3 rounded-full transition">
                        <i data-lucide="instagram"></i>
                    </a>

                    <a href="#"
                        class="bg-sky-500 hover:bg-sky-600 p-3 rounded-full transition">
                        <i data-lucide="twitter"></i>
                    </a>

                    <a href="#"
                        class="bg-green-600 hover:bg-green-700 p-3 rounded-full transition">
                        <i data-lucide="message-circle"></i>
                    </a>

                    <a href="#"
                        class="bg-red-600 hover:bg-red-700 p-3 rounded-full transition">
                        <i data-lucide="youtube"></i>
                    </a>

                </div>

                <p class="text-gray-400 text-xs mt-4">
                    Mantente informado sobre herramientas legales,
                    prevención de riesgos climáticos y acceso a la justicia.
                </p>
            </div>

        </div>

        <!-- Línea divisoria -->
        <div class="border-t border-gray-700 mt-10 pt-6 text-center">

            <p class="text-sm text-gray-400">
                © 2026 AMPARO CLIMÁTICO | Proyecto de Legal Design para la Justicia Climática.
            </p>

            <p class="text-xs text-gray-500 mt-2">
                Diseñado para democratizar el acceso al conocimiento jurídico
                y fortalecer la resiliencia de los sectores productivos de Arequipa.
            </p>

        </div>

    </div>

</footer>
</body>

</html>

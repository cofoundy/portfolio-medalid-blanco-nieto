# Propuesta de Diseno: Medalid Blanco Nieto

## Identidad
Medalid es una ingeniera electrónica peruana que construyó 25+ años de carrera corporativa en TIC (Perú y Australia), gestionando contratos gubernamentales de $18M+. Ahora está haciendo la transición más valiente de su vida: usar toda esa experiencia corporativa para empoderar a personas y organizaciones en bienestar financiero. No es una coach teórica — viene de las trincheras corporativas y entiende de primera mano cómo el estrés financiero destruye productividad.

## Audiencia
- **Directores de HR/L&D corporativos** buscando facilitadora de talleres de bienestar financiero (B2B)
- **Individuos** buscando coaching financiero personal (B2C)
- **Profesionales latinos en Australia** que conectan con su background bicultural

## Secciones Propuestas (en orden)

1. **Nav** — Floating pill nav, minimal (About, Workshops, Contact)
2. **Hero** — Nombre serif grande + "Empowering You to Build Financial Confidence" + CTA "Book a Consultation". Sin foto (no enviada). Gradient cálido beige→bronze sutil.
3. **The Challenge** — Stat animado "60%+" de trabajadores con estrés financiero. 4 impactos en lista (lower focus, poor decisions, absenteeism, turnover). Mensaje: "What seems personal is organizational." Fondo oscuro para contraste.
4. **About Medalid** — Transición: 25+ años corporate IT → coaching certificado. Badges: Engineers Australia, UNMSM. Quote: "I meet people where they are." Storytelling, no bullet points.
5. **The Path** (SECCION UNICA) — Los 3 talleres como camino visual progresivo con línea conectora animada: Money Management Fundamentals → Financial Fitness → Money Mindset. En mobile: vertical stacked con línea central. En desktop: horizontal 3-col.
6. **Why Medalid** — 4 cards con diferenciadores: Practical Strategies, Reduced Stress, No-Judgment Style, All Levels Content.
7. **Contact** — CTA grande "Let's Start the Conversation" + email info@blanconieto.com + WhatsApp +61414628494 + lunes-sábado by appointment.

## Secciones que NO incluir
- **Skills pills** — irrelevante para coach; su expertise se demuestra, no se lista
- **Education section** — su grado está mencionado en About; sección dedicada sería genérica
- **Experience timeline** — su carrera IT es backstory en About, no el foco
- **Testimonials** — no tiene; placeholder se siente falso
- **Projects grid** — no tiene "proyectos" visuales
- **Blog** — no solicitado

## Metafora Visual
Un salón de consultoría bañado en luz cálida — suficientemente profesional para comandar respeto, suficientemente cálido para sentirse segura compartiendo ansiedades financieras. Beige arena + bronze dorado + espresso oscuro.

## Paleta (6 colores)
- **primaryDark:** #2A1F14 — Espresso profundo. Headings, footer bg, nav. Evoca profundidad y confianza sin el frío del negro puro.
- **primary:** #8C7248 — Bronze. SU color de marca actual (rgb 140,114,72). Bordes, shimmer, badges.
- **primaryLight:** #C4A97A — Gold suave. Highlights, shimmer bars.
- **accent:** #C67D3E — Warm amber. CTAs, stats, dots. Gold=dinero, confianza, energía. Pop contra beige.
- **surface:** #F2EAE0 — Beige (solicitado explícitamente). Fondos de secciones.
- **surfaceLight:** #FAF7F2 — Warm white. Hero bg, secciones claras.

## Tipografia
- **Headings:** Cormorant Garamond — Serif elegante, evoca mundo financiero/premium, sofisticada pero no fría
- **Body:** Work Sans — Friendly, moderna, altamente legible, complementa la formalidad de Cormorant
- **Accent:** Cormorant Garamond italic para quotes/taglines

## Efecto Visual Unico
1. **Workshop Path Animation** — Los 3 pasos del camino con línea animada SVG que se dibuja al hacer scroll, dots que "pulse" al llegar
2. **Animated Counter** — El "60%+" en The Challenge cuenta de 0 a 60 con easing

## Motion Design
- Corporativo-coach → minimal pero con calor
- Hero: fadeIn + subtle stagger en texto
- Scroll reveals: solo opacity + translateY (nada exagerado)
- The Path: line-draw SVG animation (unique)
- Counter: number count-up animation
- `prefers-reduced-motion`: solo opacity

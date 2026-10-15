# Dental Costa Adeje — Propuesta 2: Boutique Dental Concierge & Esthetic (2026)

Rediseño galardonado (Awwwards / Behance standard) para **Costa Adeje Dental Center** (Tenerife Sur), bajo la dirección de diseño **"Boutique Dental Concierge & Esthetic"**.

## 🎨 Identidad Visual y Experiencia (UX)
- **Modo Oscuro Editorial Refinado**: Fondo antracita profundo (`#0E131F`, evitando negros puros `#000000` para prevenir fatiga visual).
- **Acento Champagne Mate**: Tonalidad oro champagne (`#CFB16C`) con micro-interacciones suaves (0.28s) y bordes resplandecientes.
- **Glassmorphism / Liquid Glass**: Tarjetas con `backdrop-filter: blur(16px)`, `background: rgba(22, 28, 45, 0.75)` y `border: 1px solid rgba(207, 177, 108, 0.2)`.
- **Tipografía Editorial**: *Playfair Display* para titulares de alta costura + *Outfit* para cuerpo de lectura (>=18px en desktop, >=16px en móvil, line-height 1.65em).
- **Smile Comparison Slider Interactivo**: Widget funcional de pantalla dividida con arrastre fluido de ratón y pantalla táctil (`smile_before.webp` vs `smile_after.webp`).
- **Servicio Concierge VIP**: Módulo de transporte privado en furgoneta Mercedes VIP desde el Aeropuerto Tenerife Sur (TFS) y hoteles 5 estrellas de Costa Adeje, lounge privado de recuperación y coordinador bilingüe.
- **Autoridad Médica (E-E-A-T)**: Acreditaciones oficiales del Colegio de Dentistas de Santa Cruz de Tenerife (COEST): Dra. Ana Isabel Martín Fuster (Directora Médica, COEST 38000742), Dr. Facundo Mateo Ríos (Director Quirúrgico, COEST 38000921), Dra. Maryuri de Castro (Ortodoncia, COEST 38000855).
- **Conversión CRO & Multilingüe**:
  - Enlace telefónico canónico `tel:+34683101030`.
  - Botón flotante radar de WhatsApp con mensaje contextualizado.
  - Barra de acción rápida fija inferior en móviles (<= 768px).
  - Selector multilingüe interactivo para 4 idiomas (ES, EN, DE, IT).

## 📁 Estructura de Archivos
```
propuesta-2-boutique-concierge/
├── index.html                   # Prototipo interactivo HTML5 semántico responsive
├── elementor-template.json      # Plantilla Elementor Pro v0.4 (100% Flexbox Containers)
├── README.md                    # Documentación técnica
├── .gitignore                   # Exclusiones de control de versiones
└── assets/                      # Activos multimedia 100% WebP < 90 KB y spritesheet SVG
    ├── hero_boutique_dark.webp
    ├── smile_before.webp
    ├── smile_after.webp
    ├── clinica_doctora_consulta.webp
    ├── doctor_facundo_mateo.webp
    ├── doctora_maryuri_castro.webp
    ├── transporte_vip_shuttle.webp
    ├── logo_costa_adeje_dental.webp
    ├── marca_*.webp
    └── spritesheet_dental_icons.svg
```

## 🚀 Despliegue en GitHub
Este repositorio cuenta con su origen remoto configurado hacia:
```bash
https://github.com/Freitech2020/dental-costa-adeje-propuesta-2.git
```

Para subir los cambios:
```powershell
git push -u origin main
```

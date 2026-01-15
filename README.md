# CV – Alejandro Gaon

Curriculum Vitae implementado en **Markdown**.  
El repositorio está diseñado para **exportar el CV a PDF, DOCX y HTML** a partir de una única fuente de verdad (`cv.md`).

---

## 📄 Estructura del proyecto

```
├── cv.md
├── README.md
├── exports/
│ ├── pdf/
│ ├── docx/
│ └── html/
├── scripts/
│ └── export.sh
└── assets/
```

---

### Descripción de carpetas
- **cv.md** → Fuente única del CV (Markdown)
- **exports/** → Versiones finales listas para compartir
- **scripts/** → Scripts de automatización de exportación
- **assets/** → Recursos opcionales (imágenes, íconos, etc.)

---

## 🚀 Exportar el CV

Este proyecto utiliza **Pandoc** para generar los distintos formatos a partir de `cv.md`.

---

## ⚙️ Requisitos

- Pandoc  
- LaTeX (para exportar a PDF)

Instalación en WSL / Linux:
```bash
sudo apt update
sudo apt install pandoc texlive-xetex


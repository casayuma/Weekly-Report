# Instrucciones del proyecto

## MarkItDown — conversión automática de archivos

Cuando el usuario pida leer, analizar o procesar cualquiera de los siguientes tipos de archivo, **siempre conviértelo primero a Markdown usando MarkItDown** antes de leerlo:

| Tipo | Extensiones |
|------|-------------|
| PDF | `.pdf` |
| Word | `.docx`, `.doc` |
| Excel | `.xlsx`, `.xls` |
| PowerPoint | `.pptx`, `.ppt` |
| Imagen | `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.webp` |
| Audio | `.mp3`, `.wav`, `.ogg`, `.m4a` |
| Video | `.mp4`, `.mov`, `.avi`, `.mkv` |
| HTML | `.html`, `.htm` |
| CSV | `.csv` |

### Cómo usar MarkItDown

```bash
markitdown /ruta/al/archivo.pdf > /tmp/archivo_converted.md
```

Luego lee `/tmp/archivo_converted.md` con la herramienta Read.

### Herramienta instalada

- **Paquete:** `markitdown[all]` v0.1.5 (Microsoft)
- **Instalado en:** `/usr/local/bin/markitdown`
- **ffmpeg:** instalado (soporte de audio/video)

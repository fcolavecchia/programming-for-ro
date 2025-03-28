# taller-de-informatica
Curso de taller de informática para Física Médica - 2020 - 2021

## Cómo generar el libro?

Desde el directorio de idioma `es/`:

```bash
uv run jupyter-book build .
```

## Cómo subir el libro a la web?

```bash
uv run ghp-import -n -p -f -b es-2025 _build/html
``` 



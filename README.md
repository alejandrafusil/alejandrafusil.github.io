# Portafolio — Alejandra Fusil Palencia

Portafolio personal de **Alejandra Fusil Palencia**, Full Stack Developer · Integración de IA · SaaS B2B.

Sitio estático de un solo archivo (HTML + CSS + JS embebidos), bilingüe (ES/EN).

## Estructura

```
.
├── index.html                 # Portafolio (página principal)
├── assets/
│   └── CV_AlejandraFusil.pdf   # CV descargable
├── .gitignore
└── README.md
```

## Ver localmente

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Publicar en GitHub Pages

1. Sube el contenido de esta carpeta al repositorio.
2. En **Settings → Pages**, elige la rama (`main`) y carpeta `/root`.
3. El sitio quedará disponible en `https://<usuario>.github.io/<repo>/`.

El botón **Descargar CV** usa una ruta relativa (`assets/CV_AlejandraFusil.pdf`),
por lo que funciona tanto en local como después del deploy.

## Contacto

- Email: alejandrafusil@gmail.com
- LinkedIn: https://linkedin.com/in/alejandrafusil

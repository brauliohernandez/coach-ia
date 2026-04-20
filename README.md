# Paceit — Running IA

## Setup

1. Clona el repo
2. Copia el archivo de configuración:
   ```bash
   cp config.example.js config.js
   ```
3. Abre `config.js` y pega tu API key de Anthropic:
   ```js
   window.PACEIT_CONFIG = {
     apiKey: 'sk-ant-...'
   };
   ```
4. Abre `index.html` con Live Server en VS Code

## ⚠️ Importante
- `config.js` está en `.gitignore` — nunca se sube a GitHub
- `config.example.js` es la plantilla pública sin key
- Nunca pongas tu API key directamente en `index.html`

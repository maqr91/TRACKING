
# Rastreo Maura Multiservices (estático + Google Sheets)

Este paquete contiene un `index.html` que consulta tu Google Apps Script para mostrar el estado de un envío por número de guía.

## Cómo usar en tu Mac
1) Descomprime este ZIP en tu Escritorio.
2) Abre la carpeta `rastreo-maura`.
3) Haz doble clic en `index.html` para probarlo local.
4) Para publicarlo:
   - Ve a https://vercel.com
   - Inicia sesión.
   - + Add New… → Project
   - Arrastra la carpeta `rastreo-maura` y presiona **Deploy**.

## Cambiar datos de contacto o logo
- Edita `index.html` con TextEdit.
- Busca el bloque `<footer>` para teléfono/correo.
- Cambia el `src` de la etiqueta `<img>` del header por tu logo.

## API de Google Apps Script
Ya viene con tu URL pegada. Si alguna vez la cambias:
- Abre `index.html`
- Modifica la constante `API_URL` con la nueva URL.

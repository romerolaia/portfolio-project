# Entrega para Claude Code · Criptika + portfolio (25 de octubre de 2026)

Repositorio: romerolaia/portfolio-project, rama main. Copiar cada archivo en la misma ruta, sustituyendo el existente.

## Sustituir
- apps/criptika/privacy/index.html — política de privacidad final
- apps/criptika/terms/index.html — términos finales (EULA estándar de Apple)
- apps/criptika/support/index.html — soporte final
- i18n.js — traducciones ES/EN actualizadas (sirve para todo el portfolio)
- index.html, design.html, case-study-flycalm.html, apps/index.html, apps/criptika/index.html — iguales que la versión publicada, solo se ha quitado el enlace a /privacy/ del pie de página

## Añadir si no existen
- assets/fonts/fonts.css, Inter (woff2), BricolageGrotesque-ExtraBold.ttf y sus licencias
- assets/criptika/icon.png

## Eliminar del despliegue
- privacy/index.html (privacidad general de la web, sigue en borrador). Borrar la carpeta privacy/ y hacer commit.

## Después
1. Commit y push a main; comprobar que Vercel despliega.
2. Comprobar que responden sin iniciar sesión:
   - https://www.laiaromerodesign.com/apps/criptika/privacy/
   - https://www.laiaromerodesign.com/apps/criptika/terms/
   - https://www.laiaromerodesign.com/apps/criptika/support/
   y que https://www.laiaromerodesign.com/privacy/ ya no existe.
3. En la app: poner las URL de privacidad y términos en Criptika/Services/Subscriptions/LegalLinks.swift y las tres en App Store Connect.

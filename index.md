---
layout: home
title: "Valynx Legal"
---
<style>
  h1 {
    font-size: 2.4rem;
    font-weight: 700;
    margin-bottom: 1rem;
  }
  h2 {
    margin-top: 2rem;
    font-size: 1.6rem;
    font-weight: 600;
  }
  body, p, li {
    font-size: 1.05rem;
    line-height: 1.6;
  }
  ul {
    margin-top: 1rem;
  }
</style>

<script>
  const params = new URLSearchParams(window.location.search);
  const base = "/valynx-legal";

  // 1. Si la app envía ?lang=xx → redirigir directamente
  if (params.has("lang")) {
    const lang = params.get("lang").toLowerCase();
    window.location.href = `${base}/${lang}/privacy.html`;
  } 
  // 2. Si vienes desde "Volver al inicio" → no redirigir
  else if (params.has("from")) {
    console.log("Mostrando index sin redirección");
  } 
  // 3. Si entras desde navegador → autodetección normal
  else {
    const lang = navigator.language.substring(0, 2).toLowerCase();
    const supported = ["es", "en", "fr", "de", "pt", "it"];

    if (supported.includes(lang)) {
      window.location.href = `${base}/${lang}/privacy.html`;
    } else {
      window.location.href = `${base}/en/privacy.html`;
    }
  }
</script>

# Valynx – Documentación Legal

Bienvenido a la sección legal de Valynx. Si no eres redirigido automáticamente, selecciona tu idioma:

## 🌍 Selecciona tu idioma:

- 🇪🇸 [Español](/valynx-legal/es/privacy.html)
- 🇬🇧 [English](/valynx-legal/en/privacy.html)
- 🇫🇷 [Français](/valynx-legal/fr/privacy.html)
- 🇩🇪 [Deutsch](/valynx-legal/de/privacy.html)
- 🇵🇹 [Português](/valynx-legal/pt/privacy.html)
- 🇮🇹 [Italiano](/valynx-legal/it/privacy.html)

---

📧 **Contacto corporativo:**  
**valynxsolutions@outlook.com**

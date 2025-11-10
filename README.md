# Rombux Email Templates

Repositorio para gestionar, versionar y colaborar en los templates HTML de email para campañas institucionales, servicios, educativos y eventos.

## Estructura sugerida

```
institucional/
  institucional.html
servicios/
  servicios.html
educativo/
  educativo.html
eventos/
  eventos.html
assets/
  logo.png
  banner-eventos.jpg
docs/
  guia-de-test.md
```

## ¿Cómo usar los templates?

1. Edita los archivos HTML según el diseño aprobado en Figma.
2. Exporta y sube los recursos gráficos usados (`assets/`).
3. Para testear la visualización, sube el HTML a la plataforma Emblue o usa herramientas como [Litmus](https://litmus.com/) o [Email on Acid](https://www.emailonacid.com/).
4. Mantén los estilos `inline` y evita CSS externo para máxima compatibilidad.
5. Asergura compatibilidad con clientes de email populares (Gmail, **Outlook**, Apple Mail).

## Colaboración

- Para nuevos templates, crea una carpeta y sube el HTML.
- Para cambios, usa PR y describe el objetivo.
- Para nuevas campañas, crea issues con detalles del contenido y diseño.

## Enlaces útiles

- Diseño en Figma: [Mails Rombux](https://www.figma.com/design/ErEBhLV8Xj1NnMxy0zSncs/Mails-Rombux?node-id=1-4&t=e26O76pPRuzJtnIv-1)
- Emblue: https://embluemail.com/

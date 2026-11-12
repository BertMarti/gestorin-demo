# 1. Empezar

[← Índice](README.md)

## Instalar

- **Windows:** descarga el instalador `.exe` de la última versión en
  [Releases](https://github.com/BertMarti/gestorin/releases/latest) y ábrelo. Si Windows avisa de que
  no conoce la aplicación, pulsa *Más información → Ejecutar de todas formas*. Gestorín aún no está
  firmado (ver el [README](https://github.com/BertMarti/gestorin#si-windows-no-te-deja-instalarlo)).
- **Android:** descarga el archivo `.apk` y ábrelo. El móvil te pedirá permiso para instalar apps de
  origen desconocido.

## Crear tu archivo

La primera vez, Gestorín te pide una **frase** que solo sepas tú. Con ella se cifra todo lo que
guardes.

> **Importante:** si olvidas la frase, nadie puede recuperar tus datos, ni nosotros. Apúntala en un
> lugar seguro (un gestor de contraseñas, por ejemplo).

¿Ya usas Gestorín en otro dispositivo? Elige **«Ya lo uso en otro dispositivo»** y pon la dirección de tu
servidor, su clave y tu frase (ver [Privacidad y copias](08-privacidad-y-copias.md)).

## ¿Quién lee tus documentos?

| Opción | Cómo funciona | Para quién |
|---|---|---|
| **Gratis, en tu ordenador** (recomendada) | Un modelo de IA en tu propio equipo o en otro de tu casa (Ollama). Nada sale de casa | La mayoría |
| **Sin IA** | Lee el texto en tu dispositivo y saca fechas e importes. No explica el documento | Si no tienes Ollama o no quieres usar ninguna IA |
| **Claude** (de pago) | La lectura más fiable; cada documento cuesta unos céntimos, con tu clave | Si quieres la máxima precisión |

Si no tienes Ollama, también puedes añadir **Gemini con tu clave de pago** o **Groq**. Gestorín te
pregunta antes de enviar cada documento. Gemini gratis, NVIDIA y OpenRouter `:free` no se ofrecen: sus
condiciones no lo permiten ([por qué](../legal/proveedores.md)).

Si en la bienvenida no hay un lector en tu ordenador (en el móvil, casi siempre), Gestorín propone
**Sin IA**, para que tu primera carta se lea en vez de fallar. Puedes cambiarlo cuando quieras en
**Ajustes**.

**Ajustes**, de arriba abajo:
1. Familia.
2. Avisos.
3. Quién lee tus documentos.
4. Copia de seguridad.
5. Tu comunidad.
6. Actualizaciones.
7. Ayuda y seguridad.

Justo después de Familia está **Pasar mis ajustes a otro móvil**. Lo técnico está al final, en
**Opciones avanzadas**: sincronizar con tu propio servidor, vigilar la carpeta de descargas e informar
de un problema.

## El recorrido

Al terminar, un recorrido de seis pasos te enseña Inicio. Puedes saltarlo con **Esc** y repetirlo
desde **Ajustes → Ayuda y seguridad → Repetir el recorrido**.

<p align="center"><img src="img/movil-recorrido.jpg" alt="Recorrido de primer uso en el móvil" width="280"></p>

[Siguiente: Añadir papeles →](02-anadir.md)

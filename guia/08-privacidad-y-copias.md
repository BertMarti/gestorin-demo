# 8. Privacidad y copias

[← Índice](README.md)

## Qué sale de tu equipo

- **Todo se guarda cifrado** con tu frase. Sin ella, nadie puede leerlo.
- **Gratis en tu equipo (Ollama)** y **Sin IA**: nada sale de casa.
- **Gratis en la nube**: Gestorín **pregunta cada vez**, documento a documento, antes de enviar nada.
  Estos servicios pueden usar lo que envías para mejorar sus modelos. Avisa especialmente si parece un
  informe médico o un documento de identidad.
- **Claude** (de pago): el documento se procesa fuera de la UE. Anthropic no entrena con los datos de
  su API por defecto.
- Sin anuncios, sin analíticas, sin cuentas.

## Copia de seguridad

**Ajustes → Copia de seguridad**:

1. Elige una **contraseña para la copia** (al menos 12 caracteres) y repítela.
2. **Guardar copia** crea un solo archivo `.gestorin` con todo, cifrado.
3. En otro dispositivo, o tras reinstalar: crea tu archivo, ve a Ajustes, escribe la contraseña de la
   copia y pulsa **Restaurar una copia**.

<p align="center"><img src="img/movil-copia.jpg" alt="Ajustes con la familia y la copia de seguridad" width="280"></p>

> La copia trae tus documentos, carnets, familia, calendario fiscal y avisos. **No** trae el servidor
> de sincronización ni las claves de los servicios de IA: eso se configura en cada dispositivo.

## Sincronizar entre el PC y el móvil

Con tu propio servidor en casa (una Raspberry Pi, por ejemplo), Gestorín mantiene el PC y el móvil
iguales, siempre cifrado. Ver la [guía del homelab](https://github.com/BertMarti/gestorin/blob/main/docs/HOMELAB.md).

**Si cambias la misma ficha en dos dispositivos sin conexión**, se queda la última edición y la otra no
se pierde. En la ficha verás *«Esta ficha también se cambió desde otro dispositivo… · Ver el otro
cambio»*: ahí ves cómo quedaría y eliges **Usar el otro cambio** o **Quedarme con la actual**.

<p align="center"><img src="img/escritorio-conflicto.jpg" alt="Aviso de una versión anterior en una ficha" width="640"></p>

## Informar de un problema

Si algo falla, **Ajustes → Informar de un problema → Guardar informe** crea un `.zip` en tu equipo.
Lleva la versión, el sistema y los últimos errores. Antes de guardarlo se limpia de DNI, NIE, IBAN,
nombres, correos, teléfonos, claves y rutas. **No se envía a ningún sitio**: revísalo y adjúntalo tú
si quieres.

[← Buscar y preguntar](07-buscar-y-preguntar.md) · [Siguiente: Preguntas frecuentes →](09-preguntas.md)

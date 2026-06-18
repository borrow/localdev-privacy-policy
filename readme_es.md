# Política de Privacidad

**Fecha de vigencia: 18 de junio de 2026**

LocalDev ("nosotros", "nuestro" o "la Aplicación") es una aplicación de simulación de ubicación que muestra tu ubicación en un mapa y te permite simular ubicaciones GPS en tu dispositivo para fines de desarrollo y prueba.

Esta Política de Privacidad explica cómo recopilamos, usamos y protegemos tu información cuando usas nuestra Aplicación.

---

## 1. Información que Recopilamos

### 1.1 Información que Proporcionas
- **Configuración de Ubicación Simulada**: Cuando activas la simulación de ubicación, esta información se almacena localmente solo en tu dispositivo.

### 1.2 Información Recopilada Automáticamente
- **Datos de Ubicación**: 
  - **Ubicación Precisa**: Se usa para centrar el mapa en tu posición actual y mostrar tu ubicación. Estos datos se procesan en el dispositivo y NO se envían a nuestros servidores.
  - **Ubicación Aproximada**: Puede ser usada por Google AdMob para personalización de anuncios (solo si consientes).
  
- **Información del Dispositivo**: 
  - Tipo de dispositivo, versión del sistema operativo
  - Versión de la aplicación y estadísticas de uso
  - ID de Publicidad de Google (para servicio de anuncios, si consientes)
  - Identificador de instancia de la app, eventos de uso y diagnóstico (Firebase Analytics, solo si consientes — ver Sección 2.3)
  - Diagnósticos de fallos y estabilidad (Firebase Crashlytics, solo si consientes)

### 1.3 Recopilación de Datos por Terceros

**Google AdMob (Publicidad)**

Cuando usas la versión gratuita de nuestra Aplicación con anuncios, Google AdMob puede recopilar:
- Identificadores del dispositivo (ID de Publicidad, Android ID)
- Dirección IP y ubicación aproximada
- Datos de interacción con anuncios (impresiones, clics)
- Información del dispositivo y red

**La recopilación de datos depende de tu consentimiento:**
- **Si ACEPTAS anuncios**: Google mostrará anuncios (personalizados o genéricos, según las opciones que aceptes) y procesará los datos en consecuencia
- **Si RECHAZAS el consentimiento**: no se solicitan ni se muestran anuncios

**⚠️ IMPORTANTE: Rechazar el consentimiento pone la Aplicación en modo básico**
- Sin consentimiento de anuncios, la Aplicación funciona sin anuncios y sin la función de ubicación simulada
- Puedes aceptar los anuncios más tarde desde Ajustes para desbloquear todas las funciones

Puedes cambiar tu elección de consentimiento en cualquier momento en: **Ajustes → Gestionar consentimiento de anuncios**

**Google Firebase (Analytics y Crashlytics)**

Cuando la recopilación de datos está activada (solo si has consentido los anuncios — ver Sección 2.3), Google Firebase puede recopilar:
- Un identificador de instancia de la app y el ID de Publicidad de Google
- Eventos de uso e interacción (pantallas vistas, funciones utilizadas)
- Diagnósticos técnicos y de fallos (modelo de dispositivo, versión del SO, versión de la app, trazas de error)

**La recopilación de datos de Firebase depende de tu consentimiento:**
- **Si ACEPTAS anuncios**: se activan Firebase Analytics y Crashlytics para entender el uso y corregir fallos
- **Si RECHAZAS el consentimiento (modo básico)**: Firebase Analytics y Crashlytics quedan desactivados y no se recopilan datos de analítica ni de fallos

---

## 2. Cómo Usamos Tu Información

### 2.1 Funcionalidad de la Aplicación
- Mostrar tu ubicación en el mapa
- Habilitar la simulación de ubicación GPS
- Recordar tus preferencias (configuración de ubicación simulada)

### 2.2 Publicidad (Solo Versión Gratuita)
- Mostrar anuncios de banner e intersticiales a través de Google AdMob
- Medir el rendimiento de los anuncios
- Servir anuncios personalizados o no personalizados según tu consentimiento

### 2.3 Analítica e Informes de Fallos
Usamos **Google Firebase Analytics** y **Firebase Crashlytics** para entender cómo se usa la Aplicación y para detectar y corregir fallos y problemas de estabilidad.

- Esta recopilación está **desactivada por defecto** y solo se activa **después de que aceptes los anuncios**.
- En modo básico (consentimiento rechazado), Firebase Analytics y Crashlytics permanecen desactivados y no se recopilan datos de analítica ni de fallos.
- También usamos Firebase Remote Config para gestionar la configuración de la app; no recopila información personal.
- Usamos esta información solo de forma agregada para mejorar la Aplicación. No la usamos para identificarte personalmente.

---

## 3. Servicios de Terceros

Nuestra Aplicación integra los siguientes servicios de terceros:

### 3.1 Google AdMob (Anuncios)
- **Propósito**: Mostrar publicidad en la versión gratuita
- **Datos Recopilados**: Identificadores del dispositivo, dirección IP, datos de interacción con anuncios, ubicación aproximada
- **Política de Privacidad**: https://policies.google.com/privacy
- **Opciones de Anuncios**: Puedes optar por no recibir anuncios personalizados en la configuración de tu dispositivo o en los ajustes de la Aplicación

### 3.2 OpenStreetMap (Mapas)
- **Propósito**: Mostrar mapas
- **Datos Recopilados**: Dirección IP, solicitudes de mapas
- **Política de Privacidad**: https://wiki.osmfoundation.org/wiki/Privacy_Policy
- **Nota**: Los servidores de mapas reciben tu dirección IP al descargar imágenes de mapas

### 3.3 Photon de Komoot (Geocodificación)
- **Propósito**: Búsqueda de direcciones y geocodificación inversa
- **Datos Recopilados**: Consultas de búsqueda, coordenadas, dirección IP
- **Política de Privacidad**: https://www.komoot.com/privacy
- **Nota**: Tus búsquedas se envían a los servidores de Photon (photon.komoot.io) para encontrar direcciones

### 3.4 Google Firebase (Analytics, Crashlytics y Remote Config)
- **Propósito**: Analítica de uso, informes de fallos/estabilidad y configuración remota
- **Datos Recopilados**: Identificador de instancia de la app, ID de Publicidad de Google, eventos de uso, diagnósticos del dispositivo y de fallos
- **Política de Privacidad**: https://firebase.google.com/support/privacy
- **Nota**: La recopilación solo se activa cuando aceptas los anuncios; está desactivada en modo básico

---

## 4. Base Legal para el Procesamiento (RGPD - Usuarios EEE/UK)

Si te encuentras en el Espacio Económico Europeo (EEE) o Reino Unido, procesamos tus datos basándonos en:

### 4.1 Ejecución de un Contrato
- Proporcionar las funciones de mapa y simulación de ubicación que solicitaste

### 4.2 Consentimiento
- **Publicidad Personalizada**: Recopilamos tu consentimiento a través de la Plataforma de Mensajería de Usuario (UMP) de Google antes de mostrar anuncios personalizados
- **Publicidad No Personalizada**: Se sirve sin requerir consentimiento en algunas jurisdicciones
- Puedes retirar tu consentimiento en cualquier momento: **Ajustes → Gestionar consentimiento de anuncios**

### 4.3 Intereses Legítimos
- Mejorar la funcionalidad de la aplicación y la experiencia del usuario
- Detectar y prevenir fraudes o abusos

---

## 5. Tus Opciones de Consentimiento

### 5.1 Primer Inicio
Cuando abras la Aplicación por primera vez en el EEE/UK, verás un diálogo de consentimiento preguntando si aceptas anuncios personalizados.

**Puedes elegir:**
- ✅ **Aceptar Todo**: Google AdMob mostrará anuncios personalizados basados en tus intereses
- ⚙️ **Gestionar Opciones**: elegir propósitos y proveedores específicos; pueden mostrarse anuncios sin personalización según lo que aceptes
- ❌ **Rechazar Todo**: no se mostrarán anuncios

**⚠️ NOTA IMPORTANTE:**
- Si no consientes los anuncios, la Aplicación funciona en modo básico sin anuncios y sin la función de ubicación simulada
- Puedes aceptar los anuncios más tarde desde Ajustes para desbloquear todas las funciones

### 5.2 Cambiar Tu Elección
Puedes cambiar tu consentimiento en cualquier momento:

1. Abre la aplicación
2. Ve a **Ajustes** (icono ⚙️)
3. Toca **"Gestionar consentimiento de anuncios"**
4. Realiza tu nueva elección

Tu decisión tendrá efecto inmediatamente.

### 5.2.1 Revocar Consentimiento (Retirada)
Para **revocar/retirar** tu consentimiento para publicidad personalizada:

**Opción A - Dentro de la App (Recomendado):**
1. Abre la app LocalDev
2. Toca el icono **Ajustes** (⚙️)
3. Toca **"Gestionar consentimiento de anuncios"**
4. Selecciona **"Rechazar todo"** o ajusta propósitos individuales
5. Tu consentimiento se retirará inmediatamente

**Opción B - Centro de Anuncios de Google:**
Visita: https://myadcenter.google.com/
- Gestiona todas tus preferencias de anuncios de Google
- Deshabilita anuncios personalizados en todos los servicios de Google

**Opción C - Configuración del Dispositivo (Android):**
1. Abre **Configuración** en tu dispositivo
2. Ve a **Google → Anuncios**
3. Activa **"Inhabilitar la personalización de anuncios"**
4. O toca **"Restablecer ID de publicidad"**

**Efecto de la Retirada:**
- ✅ Google AdMob dejará de mostrar anuncios personalizados
- ✅ Aún verás anuncios no personalizados
- ✅ Puedes cambiar tu decisión en cualquier momento

**Enlace de Revocación para AdMob:**
https://borrow.github.io/localdev-privacy-policy/#revocar-consentimiento

---

## 6. Compartir Datos y Transferencias

### 6.1 No Vendemos Tus Datos
No vendemos, alquilamos ni intercambiamos tu información personal con terceros.

### 6.2 Compartir con Terceros
Compartimos datos con:
- **Google AdMob**: Para servicio de anuncios y medición
- **Google Firebase**: Para analítica de uso e informes de fallos (solo con consentimiento)
- **OpenStreetMap/Photon**: Para mapas y geocodificación

### 6.3 Transferencias Internacionales
Algunos servicios de terceros (ej. Google) pueden transferir tus datos a países fuera del EEE/UK, incluidos Estados Unidos. Estas transferencias están protegidas por:
- Marco de Privacidad de Datos UE-EE.UU.
- Cláusulas Contractuales Estándar (CCE)
- Compromisos de privacidad de Google

---

## 7. Retención de Datos

### 7.1 Datos que Almacenamos Localmente
- **Configuración de ubicación simulada**: Almacenado en tu dispositivo hasta que desinstalas la aplicación

### 7.2 Retención por Terceros
- **Google AdMob**: Retiene datos de anuncios según su política de privacidad (típicamente 2-3 meses para la mayoría de los datos)
- **Google Firebase**: Retiene datos de analítica y fallos según las políticas de Google; la retención de datos de analítica es configurable (por defecto hasta 14 meses)
- **OpenStreetMap**: Retiene registros del servidor temporalmente para fines de seguridad

### 7.3 Eliminar Tus Datos
Para eliminar todos los datos de la aplicación:
1. Desinstala la aplicación de tu dispositivo
2. Borra el ID de Publicidad de Google: **Ajustes → Google → Anuncios → Restablecer ID de publicidad**

---

## 8. Tus Derechos de Privacidad

Dependiendo de tu ubicación, puedes tener los siguientes derechos:

### 8.1 Usuarios EEE/UK (RGPD)
- ✅ **Derecho de Acceso**: Solicitar una copia de tus datos
- ✅ **Derecho de Rectificación**: Corregir datos inexactos
- ✅ **Derecho de Supresión**: Solicitar la eliminación de tus datos
- ✅ **Derecho de Restricción**: Limitar cómo usamos tus datos
- ✅ **Derecho a la Portabilidad de Datos**: Recibir tus datos en un formato portátil
- ✅ **Derecho de Oposición**: Oponerte al procesamiento basado en intereses legítimos
- ✅ **Derecho a Retirar el Consentimiento**: Retirar consentimiento para anuncios personalizados en cualquier momento
- ✅ **Derecho a Presentar una Queja**: Presentar una queja ante tu autoridad local de protección de datos

### 8.2 Usuarios de California (CCPA/CPRA)
- ✅ **Derecho a Saber**: Qué información personal recopilamos y cómo la usamos
- ✅ **Derecho a Eliminar**: Solicitar la eliminación de tu información personal
- ✅ **Derecho a Optar por No Participar**: Optar por no participar en la venta de información personal (Nota: No vendemos tu información)
- ✅ **Derecho a No Discriminación**: No discriminaremos contra ti por ejercer tus derechos

### 8.3 Otras Jurisdicciones
Los usuarios en otras jurisdicciones pueden tener derechos similares bajo las leyes locales de privacidad.

### 8.4 Ejercer Tus Derechos
Para ejercer tus derechos:
- **Para datos de la aplicación**: Desinstala la aplicación o ajusta la configuración
- **Para datos de AdMob**: Visita https://myadcenter.google.com/ o contacta a Google
- **Consultas generales**: Contáctanos en cgborrow@gmail.com

---

## 9. Seguridad

Implementamos medidas de seguridad razonables para proteger tu información:
- ✅ Todos los datos almacenados localmente en tu dispositivo están protegidos por las funciones de seguridad de Android
- ✅ Las conexiones a servicios de terceros usan cifrado HTTPS
- ✅ No almacenamos datos personales en nuestros propios servidores

Sin embargo, ningún método de transmisión por internet es 100% seguro. Aunque nos esforzamos por proteger tu información, no podemos garantizar seguridad absoluta.

---

## 10. Privacidad de los Niños

Nuestra Aplicación **no está dirigida a niños menores de 13 años** (o 16 en el EEE).

No recopilamos intencionalmente información personal de niños. Si eres padre o tutor y crees que tu hijo nos ha proporcionado información personal, contáctanos y eliminaremos dicha información.

**Restricciones de Edad:**
- 🚫 Niños menores de 13 años: No deben usar esta aplicación
- 🚫 Niños del EEE menores de 16 años: No deben usar esta aplicación sin consentimiento parental

---

## 11. Permisos Explicados

Nuestra Aplicación solicita los siguientes permisos de Android:

### 11.1 Permiso de Ubicación (Requerido)
- **ACCESS_FINE_LOCATION**: Para mostrar tu ubicación precisa en el mapa
- **ACCESS_COARSE_LOCATION**: Para mostrar tu ubicación aproximada en el mapa
- **Por qué lo necesitamos**: Funcionalidad principal de la aplicación (centrado del mapa, visualización de ubicación)

### 11.2 Ubicación Simulada (Opcional)
- **Habilitado a través de Opciones de Desarrollador**: Para simular ubicaciones GPS
- **Por qué lo necesitamos**: Para proporcionar funcionalidad de simulación de ubicación

### 11.3 Permiso de Internet (Requerido)
- **INTERNET**: Para descargar mapas y realizar geocodificación
- **Por qué lo necesitamos**: La visualización de mapas requiere descargar imágenes de los servidores de OpenStreetMap

### 11.4 Estado de Red (Requerido)
- **ACCESS_NETWORK_STATE**: Para verificar conectividad a internet
- **Por qué lo necesitamos**: Para mostrar mensajes apropiados cuando estás sin conexión

### 11.5 Publicar Notificaciones (Android 13+, Opcional)
- **POST_NOTIFICATIONS**: Para mostrar una notificación en primer plano mientras la ubicación simulada está activa
- **Por qué lo necesitamos**: Android requiere una notificación persistente para servicios en primer plano

Puedes revocar permisos en cualquier momento en: **Ajustes de Android → Aplicaciones → LocalDev → Permisos**

---

## 12. Cambios a Esta Política de Privacidad

Podemos actualizar esta Política de Privacidad de vez en cuando para reflejar cambios en:
- Nuestras prácticas
- Requisitos legales
- Funciones de la aplicación

**Cuando hagamos cambios:**
- ✅ Actualizaremos la "Fecha de vigencia" al principio de esta política
- ✅ Te notificaremos a través de la aplicación o por correo electrónico (si tenemos tu correo)
- ✅ El uso continuado de la aplicación después de los cambios indica tu aceptación

**Cómo mantenerte informado:**
- Revisa esta política periódicamente para actualizaciones
- Verifica la fecha de vigencia en la parte superior

**Versiones anteriores:**
- 18 de junio de 2026: v1.33 - Añadida divulgación de Firebase Analytics y Crashlytics (sujeto a consentimiento)
- 17 de octubre de 2025: v1.2.6 - Fix crítico de persistencia de consentimiento
- 14 de octubre de 2025: v1.2.5 - Añadidas secciones de consentimiento UMP y revocación
- 9 de octubre de 2025: Versión inicial

---

## 13. Contáctanos

Si tienes preguntas, inquietudes o solicitudes relacionadas con esta Política de Privacidad o nuestras prácticas de datos, contáctanos:

**Desarrollador/Editor de la Aplicación:**
- **Email**: cgborrow@gmail.com
- **Dirección Postal**: 
  ```
  Carlos Barreda Gallardo
  Calle Amadeu Paltor 20 2 1
  08640 Olesa de Montserrat
  Barcelona, España
  ```

**Tiempo de Respuesta**: Responderemos a tu consulta dentro de 30 días.

**Delegado de Protección de Datos (si aplica en EEE/UK):**
- **Email**: [dpo-email@ejemplo.com] (si aplica)

---

## 14. Información Adicional

### 14.1 Socios de Google AdMob
Google AdMob trabaja con socios publicitarios de terceros. Para ver la lista completa de socios y sus políticas de privacidad, visita:
- **Proveedores de Tecnología Publicitaria de Google**: https://support.google.com/admob/answer/9012903

### 14.2 Tus Opciones de Anuncios
- **Configuración de Anuncios de Google**: https://myadcenter.google.com/
- **Digital Advertising Alliance (DAA)**: http://optout.aboutads.info/
- **Network Advertising Initiative (NAI)**: http://optout.networkadvertising.org/
- **European Interactive Digital Advertising Alliance (EDAA)**: http://www.youronlinechoices.eu/

### 14.3 Autoridades Supervisoras (EEE/UK)
Si crees que no estamos cumpliendo con el RGPD, puedes presentar una queja ante tu autoridad local de protección de datos:
- **Autoridades de Protección de Datos de la UE**: https://edpb.europa.eu/about-edpb/board/members_en
- **Oficina del Comisionado de Información del Reino Unido (ICO)**: https://ico.org.uk/

---

## 15. Resumen

**Lo que recopilamos:**
- ✅ Datos de ubicación (procesados en el dispositivo, no enviados a nuestros servidores)
- ✅ Identificadores del dispositivo (para anuncios, solo si consientes)
- ✅ Datos de interacción con anuncios (para anuncios, solo si usas la versión gratuita)
- ✅ Analítica de uso y diagnósticos de fallos (Firebase, solo si consientes)

**Cómo lo usamos:**
- ✅ Para mostrar tu ubicación en el mapa
- ✅ Para habilitar la simulación de ubicación
- ✅ Para mostrar anuncios (solo versión gratuita, según tu consentimiento)

**Tus opciones:**
- ✅ Aceptar o rechazar anuncios personalizados
- ✅ Cambiar tu consentimiento en cualquier momento en Ajustes
- ✅ Desinstalar la aplicación para eliminar todos los datos locales

**NO hacemos:**
- ❌ Vender tu información personal
- ❌ Almacenar datos de ubicación en nuestros servidores
- ❌ Rastrearte fuera de la aplicación

---

**Última actualización: 18 de junio de 2026**

**Versión de la Aplicación: 1.33**

**Paquete: com.localdev.app**

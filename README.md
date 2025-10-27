# Ofuscador de DNI (ODNI) 

## 📌 Sobre este proyecto

**Creado por Alfonso E.M.**

Esta herramienta nace de la necesidad de proteger nuestros datos personales en un mundo donde cada vez más entidades solicitan copias de nuestro DNI sin justificación real.

Hoteles, comercializadoras de electricidad, bancos y otras empresas frecuentemente piden fotos o copias de tu Documento Nacional de Identidad para procesos que, en muchos casos, **son innecesarios e incluso pueden ser ilegales** según la normativa de protección de datos (RGPD).

### ⚖️ ¿Por qué es importante?

- **Protección de identidad**: Las copias de DNI sin protección pueden ser usadas para suplantación de identidad
- **Minimización de datos**: Solo debes proporcionar los datos estrictamente necesarios para cada finalidad
- **Prevención de fraude**: Limita la exposición de tu información personal sensible
- **Cumplimiento normativo**: El RGPD establece que no se deben recabar más datos de los necesarios

Con esta herramienta puedes generar copias de tu DNI **marcadas específicamente para el destinatario** (ej: "copia para el hotel"), dificultando su uso fraudulento por terceros, y **difuminando áreas sensibles** que no son necesarias para el trámite en cuestión.

---

## ✨ Características

### 🔒 Seguridad y Privacidad
- **100% offline**: Funciona completamente en tu navegador, sin subir nada a internet
- **Sin servidores**: Tus imágenes nunca salen de tu ordenador
- **Código abierto**: Todo el código está disponible en un único archivo HTML

### 🎨 Funcionalidades

1. **Carga de imágenes**: Sube anverso y reverso del DNI
2. **Recorte interactivo**: Elimina márgenes sobrantes de las fotos
3. **Redimensionamiento automático**: Normaliza las imágenes a un tamaño estándar
4. **Difuminado de áreas sensibles**:
   - Foto del titular
   - Firma
   - Número de equipo (IDE)
   - Otras áreas personalizables
5. **Marca de agua personalizable**: Añade texto sobre la foto (ej: "copia para el hotel")
6. **Editor visual interactivo**: Arrastra y redimensiona las áreas con el ratón
7. **Vista previa en tiempo real**: Ve el resultado antes de procesarlo

---

## 🚀 Cómo usar

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación ni conexión a internet

### Paso a paso

1. **Abre el archivo**: Haz doble clic en `dni-processor.html`

2. **Sube las imágenes**:
   - Carga el anverso (cara frontal) del DNI
   - Carga el reverso (cara trasera) del DNI

3. **Recorta las imágenes** (opcional):
   - Arrastra sobre la imagen para seleccionar el área útil
   - Elimina márgenes o fondos innecesarios
   - Puedes omitir este paso si no es necesario

4. **Configura el procesamiento**:
   - Activa el checkbox "Mostrar áreas sin difuminar"
   - **Arrastra los rectángulos de colores** para ajustar las áreas:
     - 🔴 Rojo = Foto del titular
     - 🔵 Azul = Firma
     - 🟢 Verde = Texto "EQUIPO" (reverso)
   - Edita el texto que aparecerá sobre la foto
   - Ajusta el tamaño de fuente y color si es necesario

5. **Vista previa**:
   - Desactiva "Mostrar áreas sin difuminar" para ver el resultado final
   - Comprueba que todo está correcto

6. **Procesa y descarga**:
   - Haz clic en "🎨 Procesar imágenes"
   - Descarga el anverso procesado
   - Descarga el reverso procesado

---


### Privacidad
- Todo el procesamiento ocurre en el navegador (client-side)
- No se realizan peticiones HTTP
- No se almacenan datos en servidores externos
- No se usan cookies ni analytics

---

## 📋 Licencia y Responsabilidad

Este software se proporciona "tal cual", sin garantías de ningún tipo.

**Responsabilidad del usuario:**
- Úsalo bajo tu propia responsabilidad
- Verifica siempre que cumples con las leyes locales
- Comprueba que el resultado cumple con los requisitos del destinatario
- No uses esta herramienta para fines fraudulentos o ilegales


---




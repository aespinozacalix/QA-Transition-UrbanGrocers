# 📋 Urban Grocers API Testing Suite

## 🎯 Contexto del proyecto

Este proyecto representa una etapa clave en mi transición de **Ingeniero Industrial** a **QA Engineer**. Urban Grocers es una plataforma de delivery de comestibles, y tuve la oportunidad de diseñar y ejecutar pruebas manuales sobre dos funcionalidades críticas: la gestión de kits de productos y el cálculo de servicios de entrega.

Durante este proceso, apliqué técnicas de testing estructurado, documenté defectos reales y consolidé mis habilidades en herramientas como **Postman**, **Excel** y **JIRA**.

---

## 🔍 Análisis realizado

### 🧪 Requisito 1: Gestión de kits

- Validé los endpoints para agregar productos a kits.
- Probé parámetros como `kitId`, `productId` y `quantity`.
- Analicé límites en la estructura del array `productsList`.
- Verifiqué el máximo permitido de productos únicos por kit.

### 🚚 Requisito 2: Servicios de entrega

- Probé el cálculo de precios de envío según peso, cantidad y horario.
- Validé parámetros como `deliveryTime`, `productsWeight`, `productsCount`.
- Verifiqué la lógica de negocio en distintos rangos de entrega.

---

## 🧠 Lo que hice

- ✍️ Diseñé más de **32 casos de prueba** cubriendo escenarios positivos, negativos, clases de equivalencia y valores límite.
- 🐞 Identifiqué y documenté **bugs críticos** relacionados con validación de parámetros y cálculos de entrega.
- 📊 Utilicé **Excel** para organizar los casos de prueba, incluyendo ID, descripción, pasos, resultados esperados y reales.
- 🗂️ Registré los defectos en **JIRA**, con evidencia visual y trazabilidad.
- 🏅 Recibí mi **badge de certificación QA**, consolidando esta etapa de formación.

---

## 🧰 Herramientas utilizadas

- 🔧 **Postman** – Ejecución de pruebas de API  
- 📋 **Excel** – Documentación de casos de prueba  
- 🐛 **JIRA** – Gestión de defectos  
- 🧪 **Técnicas aplicadas:**  
  - Partición de equivalencia  
  - Análisis de valores límite

---

## 📦 Requisitos funcionales del backend – Urban Grocers

Durante el análisis del sistema, trabajé con documentación técnica que describe cómo funcionan los endpoints de kits y servicios de entrega. A partir de esta información, diseñé casos de prueba manuales para validar la lógica de negocio, los límites de parámetros y el comportamiento esperado de cada servicio.

---

### 🔁 Endpoint `api/v1/kits/:id/products`

📋 **Funcionalidad principal:**  
Este endpoint permite agregar productos existentes a un kit específico en la plataforma Urban Grocers.

⚙️ **Cómo funciona:**  
- Método: `POST`  
- URL: `{base_url}/api/v1/kits/:id/products`  
- Parámetro: `:id` = ID del kit al que quieres agregar productos

📸 Vista de la documentación técnica:

<p align="center">
  <img src="https://raw.githubusercontent.com/aespinozacalix/QA-Transition-UrbanGrocers/main/Main_kits_API.png" width="700" alt="Gestión de kits API">
</p>

---

### 📊 Restricciones por servicio de entrega

Cada servicio tiene sus propias reglas: peso permitido, número máximo de artículos, formato de datos y horarios válidos. Esta información fue clave para diseñar pruebas con valores límite, clases de equivalencia y escenarios negativos.

📸 Tabla de restricciones y lógica de cálculo:

<p align="center">
  <img src="https://raw.githubusercontent.com/aespinozacalix/QA-Transition-UrbanGrocers/main/Restricciones%20de%20los%20servicion%20de%20entrega.png" width="700" alt="Restricciones de entrega">
</p>

---

## 🧪 Casos de prueba derivados

A partir de estos requisitos, diseñé más de **35 casos de prueba manuales** que cubren:

- Escenarios positivos y negativos  
- Validación de parámetros obligatorios y opcionales  
- Pruebas con valores fuera de rango  
- Verificación de respuestas HTTP y estructura JSON
- Estado (✅ Passed / ❌ Failed)

📎 [Descargar archivo Excel de casos de prueba](https://github.com/aespinozacalix/QA-Transition-UrbanGrocers/raw/main/Proyecto_Casos_de_prueba_Urban.xlsx)

---
## 🧭 Mi historia como QA Engineer

Como Ingeniero Industrial, siempre estuve cerca de procesos de calidad, auditorías y mejora continua. Pero al descubrir el mundo del QA en software, encontré una nueva forma de aplicar mi lógica, atención al detalle y pasión por la documentación.

Este proyecto fue una oportunidad para demostrar que la calidad no solo se audita en planta, también se construye desde el código. Cada caso de prueba que diseñé, cada bug que documenté, fue parte de mi evolución como profesional técnico.

---

## 🔗 Repositorio

👉 [Ver repositorio en GitHub](https://github.com/aespinozacalix/QA-Transition-UrbanGrocers)

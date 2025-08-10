# 💱 challenge-conversor-monedas

Este proyecto es un conversor de divisas en **Java** que permite al usuario convertir montos entre diferentes monedas usando datos en tiempo real obtenidos de una API de tipos de cambio.

---

## 🎯 Objetivo del Challenge
Desarrollar una aplicación de consola en Java que:
- Muestre un menú interactivo con opciones de conversión.
- Obtenga tipos de cambio actualizados desde una API pública.
- Realice cálculos precisos y muestre los resultados con formato amigable.
- Maneje errores y validaciones para entradas inválidas o fallos de conexión.

---

## 🛠️ Funcionalidades principales
- Conversión entre **6 pares de divisas** predefinidos.
- Validación de opciones de menú y montos ingresados.
- Formateo del resultado con **separador de miles** y **dos decimales**.
- Repetición del menú hasta que el usuario decida salir.
- Manejo de errores comunes como:
  - Opción inválida.
  - Monto no numérico o negativo.
  - Error al conectar con la API.

---

## 📚 Tecnologías utilizadas
- **Java (JDK 17+)**
- **org.json** para el manejo de datos JSON de la API.
- **API de tipos de cambio** para obtener la información en tiempo real.

---

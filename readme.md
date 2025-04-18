# 🛠️ Cálculo de Coste de Instalación

Aplicación de escritorio desarrollada en Python para comparar el coste real de una instalación frente al coste presupuestado.

---

## 📌 Descripción

Esta herramienta permite calcular y visualizar de forma sencilla si una intervención técnica en una instalación ha cumplido con el presupuesto estimado.

El usuario introduce los datos requeridos, carga un archivo Excel con los registros de trabajo y el programa devuelve el análisis junto a una visualización clara de los resultados.

---

## 🚀 ¿Qué hace el programa?

El ejecutable solicita al usuario:

- ✅ Cargar un archivo Excel con las intervenciones  
- ✅ Procesar los datos  
- ✅ Introducir:  
  - Fecha de inicio de la instalación  
  - Fecha de fin  
  - Nombre de la instalación (cliente)  
  - Coste por hora (varía según técnico)  
  - Coste presupuestado  

---

## 📊 Resultados mostrados:

- 🔸 **Horas invertidas**  
- 🔸 **Coste Total** (horas × coste por hora)  
- 🔸 **Coste Presupuestado**  
- 🔸 **Diferencia** entre el coste real y el presupuestado  
- 🔸 **Estado** (Dentro / Fuera del presupuesto)

Además, se genera una gráfica comparativa con:

- Barras para **Coste Total Invertido** y **Coste Presupuestado**  
- Línea de referencia para el presupuesto

---

## 🖥️ Captura de la aplicación

![captura](Captura%20EXE.JPG)

---

## 🧰 Tecnologías utilizadas

- Python 🐍  
- pandas 📊  
- tkinter 🖼️ (para GUI)  
- matplotlib 📈 (para visualización)  
- PyInstaller 🛠️ (para generar el ejecutable)  

---

## 📦 Generación del ejecutable

Este proyecto fue convertido a `.exe` con PyInstaller, permitiendo compartirlo fácilmente sin necesidad de tener Python instalado.

---

## 📁 Estado del proyecto

✅ Funcional y probado con múltiples datasets  
🔜 Próximas mejoras: Validación de entrada, soporte para múltiples técnicos por instalación  

---

## 📄 Licencia

Proyecto creado con fines educativos y profesionales. Uso interno o para mostrar en portfolio.

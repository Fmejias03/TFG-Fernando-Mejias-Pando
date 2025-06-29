# TFG - Sistema de Detección de Malware y Asistente Conversacional con IA

Este repositorio contiene el código fuente, modelos entrenados y archivos de análisis correspondientes al Trabajo de Fin de Grado (TFG) titulado:

**“Desarrollo de un modelo de inteligencia artificial para la detección temprana de malware mediante análisis de comportamiento”**, realizado por **Fernando Mejías Pando** (UAX, 2025).

## Descripción del proyecto

Este sistema está compuesto por dos módulos principales:

1. **Modelo de detección de amenazas (backend)**  
   - Basado en Random Forest y entrenado con el dataset *Obfuscated-MalMem2022*.
   - Realiza un análisis del sistema en tiempo real y genera un informe JSON con predicciones de procesos maliciosos.

2. **Modelo de lenguaje natural (frontend)**  
   - Basado en *Mistral 7B Instruct*, cuantizado en GGUF.
   - Funciona como interfaz conversacional mediante Gradio, interpretando los resultados del análisis y resolviendo dudas del usuario.
  
Los codigos finales están dentro de la carpeta llamada: Cuadernos Terminados Para Ejecutar

# Referencias clave
Dataset: MalMem2022 - UNB Canada

Modelo LLM: Mistral 7B Instruct

Inferencia: llama.cpp (GGUF)

Interfaz: Gradio

# Licencia
Este repositorio es parte del Trabajo de Fin de Grado de Fernando Mejías Pando (Universidad Alfonso X El Sabio, 2025). Uso académico y educativo.

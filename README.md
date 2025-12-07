# Análisis de Señales en R: Correlación, Fourier & Audio
Práctica de análisis de señales en R: correlación, autocorrelación, correlación cruzada,  Transformada de Fourier, Short Time Energy y espectrograma aplicado a datos epidemiológicos y audio.

Este repositorio contiene una práctica en **R**, dividida en dos partes:

### 1) Series temporales epidemiológicas (Copenhague 1927–1967)

Se estudia la evolución temporal de la **varicela** y la **rubeola**, analizando:

- Representación gráfica comparativa
- Transformada de Fourier y detección de periodicidad
- Autocorrelación (ACF) y correlación cruzada (CCF)
- Interpretación del comportamiento temporal

Conclusión principal:  
La varicela presenta un patrón más regular y cíclico, mientras que la rubeola muestra brotes más intensos pero irregulares.

---

### 2) Procesamiento de audio real

Se analiza un archivo de voz aplicando técnicas de señal:

- Short Time Energy (STE) con ventanas de 10 ms y 1 ms
- Representación temporal de energía del audio
- Espectrograma en frecuencia (FFT)

Resultado:  
Una ventana corta (1 ms) da más detalle pero introduce ruido visual, 10 ms es más estable para interpretar energía en habla.

---

##  Contenido del repositorio

| Archivo | Descripción |
|--------|-------------|
| `practica_analisis_senales.Rmd` | Código reproducible en RMarkdown |
| `Copenhagen.csv` | Datos epidemiológicos históricos |
| `Buenos_dias.wav` | Audio utilizado para el análisis |
| `practica_analisis_senales.pdf` | Informe compilado con resultados y gráficos |

---

## Funciones utilizadas

- **R**
- tidyverse / readr
- seewave
- tuneR
- fft / análisis espectral

---

##  Ejecución

1. Abrir el archivo `.Rmd`  
2. Knit a HTML o PDF  
3. Visualizar gráficos y espectrograma


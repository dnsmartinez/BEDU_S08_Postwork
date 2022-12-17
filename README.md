# BEDU-Santander: Proyecto final

## Problema: "Análisis de la Inseguridad Alimentaria en México"               

Un centro de salud nutricional está interesado en analizar estadísticamente y probabilísticamente los patrones de gasto en alimentos saludables y no saludables en los hogares mexicanos con base en su nivel socioeconómico, en si el hogar tiene recursos financieros extras al ingreso y en si presenta o no inseguridad alimentaria. Además, está interesado en un modelo que le permita identificar los determinantes socioeconómicos de la inseguridad alimentaria.
        
La base de datos es un extracto de la Encuesta Nacional de Salud y Nutrición (2012) levantada por el Instituto Nacional de Salud Pública en México. 

La mayoría de las personas afirman que los hogares con menor nivel socioeconómico tienden a gastar más en productos no saludables que las personas con mayores niveles socioeconómicos y que esto, entre otros determinantes, lleva a que un hogar presente cierta inseguridad alimentaria.
                     
La base de datos contiene las siguientes variables:
  - nse5f (Nivel socieconómico del hogar): 1 "Bajo", 2 "Medio bajo", 3 "Medio", 4 "Medio alto", 5 "Alto". 
  - area (Zona geográfica): 0 "Zona urbana", 1 "Zona rural".
  - numpeho (Número de personas en el hogar).
  - refin (Recursos financieros distintos al ingreso laboral): 0 "no", 1 "sí".
  - edadjef (Edad del jefe/a de familia).
  - sexoje (Sexo del jefe/a de familia): 0 "Hombre", 1 "Mujer".
  - añosedu (Años de educación del jefe de familia).
  - ln_als (Logarítmo natural del gasto en alimentos saludables).
  - ln_alns (Logarítmo natural del gasto en alimentos no saludables).
  - IA (Inseguridad alimentaria en el hogar): 0 "No presenta IA", 1 "Presenta IA".
        

![gráfica del resumen estadístico](https://github.com/dnsmartinez/BEDU_S08_Postwork/blob/main/figs/s08_postwork_summary.png)
![gráfica del gasto en alimentos saludables y no saludables](https://github.com/dnsmartinez/BEDU_S08_Postwork/blob/main/figs/s08_postwork_corr.png)

# Objetivo del Notebook:
# Llevar a cabo la creación de tres modelos de clasificación (Naive Bayes, Árbol de Decisión, KNN) para la identificación del tipo de negocio al cual pertenece una personalidad de acuerdo con sus variables socioeconómicas (Age, Female, Years, Certificates, Feedback, Salary).
# Posteriormente, se busca ver qué modelo es mejor clasificando binariamente por medio de sus métricas de evaluación. Esto para luego generar clústeres / segregaciones en base a correlaciones entre variables.
# Se busca generar 2 casos hipotéticos que no existen inicialmente en el dataset para ver en que agrupación se encontrarían y la probabilidad de ser eso cierto o no.
# Y encontrar otros conocimientos al realizar un análisis con lupa en múltiples variables que comprenden este dataset

# Descripción del dataset:
# 'Sales_Rep' = 'ID' del asesor
# 'Business' = El departamento al que pertenece
# 'Age' = Edad del asesor
# 'Female' = Variable binaria que indica género femenino cuando es 1
# 'Years' = Años desde que entró a la empresa
# 'College' = Variable categórica ordinal que indica si el asesor tiene un diploma de universitario
# 'Personality' = Variable categórica nominal que indica la personalidad del asesor
# 'Certficates' = Número de diplomas / certificados que posee el asesor
# 'Feedback' = Escala de 1 a 4 que indica la retroalimentación del asesor para la empresa, siendo 1 la más baja y 4 la más alta
# 'Salary' = Salario anual del asesor en USD
# 'NPS' = Employee Net Promoter Score. Mide la lealtad, el compromiso y la satisfacción general del personal hacia su empresa
# 'Business_Num' = Variable binaria que índica departamento de Software cuando es 1

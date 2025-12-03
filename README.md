# SAA_Trabajo_EV1
Análisis exploratorio de datos para Sistemas de Aprendizaje Automático

En este trabajo, hecho en jupyter notebook y en google colab, haremos un análisis exploratorio de datos de un dataset descargado de kaggle, con las características que se explicaron en el siguiente enunciado:

## 📄 Enunciado del Trabajo Final de la Primera Evaluación  
*(Fuente: PDF entregado por el profesor)*

### **Instrucciones generales**
- Elaborar un Colab y subir el fichero dentro del plazo establecido.  
- El fichero debe llamarse: `EV1_nombre_apellido1_apellido2_dni.ipynb`  
- Todo punto debe estar argumentado con explicaciones claras y concisas.  
- Se debe grabar un vídeo (máx. 10 minutos) explicando brevemente cómo se ha abordado cada apartado.  
- Ponderación: **70% trabajo + 30% defensa en vídeo**.  
- Si algún punto no se puede abordar (por ejemplo, falta una variable categórica), se permite **modificar o crear datos sintéticos** para cumplir el requisito.

---

## 🧩 **Puntos del trabajo**

### **1. Extracción de datos (UT4.3)**
Se puede obtener el dataset desde:
- Kaggle (CSV, JSON, TXT, etc.)  
- El enlace del Aula Virtual (UT4/Datasets)  
- Una base de datos relacional  
- Una hoja de cálculo  
- Un webcrawler  
- Otras fuentes de datos  
- O incluso crear tu propio dataset (numéricas + categóricas)

---

### **2. Análisis de variables y tipos de datos (UT4.11)**
Debes:
- Identificar variables predictoras y la variable objetivo  
- Determinar tipo de dato de cada variable  
- Identificar el tipo de problema (regresión, clasificación…)  
- Realizar representaciones gráficas

---

### **3. Datos missing (UT4.4)**
- Imputar valores faltantes si es necesario usando media, moda, mediana, etc.  
- Justificar la imputación.

---

### **4. Codificación de variables categóricas (UT4.4)**
- Crear variables con **one-hot encoding**  
- Si no existen categóricas, **crearlas de forma sintética**  
- Evitar la **trampa de las variables dummy**

---

### **5. Distribución de variables (UT4.6, UT4.11)**
- Analizar tipo de distribución  
- Calcular **skewness** y **kurtosis**  
- Representar gráficamente  
- Redactar conclusiones

---

### **6. Valores anómalos - Outliers (UT4.2)**
- Analizar outliers mediante el gráfico más adecuado  
- Redactar conclusiones

---

### **7. Correlación entre variables (UT4.9)**
- Analizar correlaciones (positivas / negativas)  
- Mostrar mapas de calor, pairgrids, scatterplots…  
- Identificar variables importantes  
- Identificar variables prescindibles  
- Redactar conclusiones

---

### **8. Ingeniería de variables (UT4.8, UT4.11)**
- Crear nuevas variables combinando, transformando o modificando existentes  
- Analizar si estas nuevas variables aumentan la correlación con la variable objetivo

---

### **9. Normalización y estandarización (UT4.10)**
- Transformar distribuciones (logaritmo u otros métodos)  
- Comparar skewness y kurtosis antes y después  
- Aplicar **StandardScaler** o **MinMaxScaler**

---

### **10. Importancia de variables (UT4.10, UT4.11)**
- Dividir dataset entre entrenamiento y validación  
- Entrenar un modelo con `sklearn`  
- Obtener **importancia de variables**  
- Extraer conclusiones

---

## ✔️ **Objetivo final**
Construir un análisis exploratorio sólido, argumentado y bien visualizado, que prepare el dataset para un modelo de aprendizaje automático.

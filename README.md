# Cancer-Pulmonar


En este proyecto se implementa redes neuronales convolucionales (CNN) para clasificar automáticamente imágenes de un subset de datos que contiene 15000 imágenes histopatológicas con 3 clases.

### **•** Tejido pulmonar benigno.

### **•** Adenocarcinoma de pulmón.

### **•** Carcinoma de células escamosas de pulmón.

Todas las imágenes tienen un tamaño de 768x768 píxeles y están en formato JPEG.

Las imágenes se generaron a partir de una muestra original de fuentes compatibles con HIPAA (normativa de privacidad médica en EE.UU.) y validadas, que consistían en:

750 imágenes originales de tejido pulmonar (250 tejidos benignos, 250 adenocarcinomas y 250 carcinomas de células escamosas).

Estas imágenes se aumentaron a 15000 usando el paquete Augmentor, quedando la clase del subset cada una con 5000 imágenes.

Dataset:

[Borkowski AA, Bui MM, Thomas LB, Wilson CP, DeLand LA, Mastorides SM. Lung and Colon Cancer Histopathological Image Dataset (LC25000). arXiv:1912.12142v1 [eess.IV], 2019 ](https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af)


Se evaluaron filtros para mejorar características diagnósticas:

### **•** Sobel (énfasis en bordes celulares)

### **•** Gaussiano (reducción de ruido)

### **•** Escala de grises (simplificación de texturas)

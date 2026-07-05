# Analisis-Embudo-Y-Retencion-MercadoLibre
Análisis para MercadoLibre enfocado en entender en que etapa del proceso de compra se pierden los usuarios y cómo mejorar su retención.

Datos: Dos tablas con columnas que incluyen información sobre los compradores, sus dispositivos utilizados, registro de actividad, país entre otros datos divididas de la siguiente manera;

mercadolibre_funnel → Registra los eventos de los usuarios durante el proceso de compra (user_id, session_id, event_name, event_times, country, device_category, platform, product_cat, price, currency, referral_source, event_date, year).

mercadolibre_retention → Mide la actividad recurrente por usuario y periodo (user_id, signup_date, signup_datetime, country, device_category, platform, day_after_signup, activity_date, active, prob_active)

📂 Contenido del repositorio

Diego-Sarinana/Analisis-Embudo-Y-Retencion-MercadoLibre - Se hizo un mapeo del embudo de conversión usando SQL llevando a cabo el siguiente proceso: 
1. Carga y exploración de esquema y datos base
2. Construcción del embudo de conversión
3. Análisis de retención y cohortes
4. Redacción de Resumen ejecutivo


▶ Cómo abrir el archivo en Google Sheets/Excel

1. Descarga el archivo dando clic al botón de 'Download raw file' tras haber abierto la sección del proyecto (Diego-Sarinana/Resumen-Ejecutivo-Ventas-Walmart)
2. En la herramienta de tu elección (Excel/Sheets) abra el archivo

O: Abre el siguiente enlace;
https://docs.google.com/spreadsheets/d/1te4De0QvxfNt20P3EwFDVfv6Tlh4OsLuODCQkebbqD8/edit?usp=sharing
  
📘 Cómo reproducir el análisis:
1. Tras abrir el archivo en la herramienta elegida puedes dar clic en las hojas de la barra inferior para revisar las modificaciones y resultados obtenidos
   
🧠 Objetivo del análisis:
1. Identificar los principales puntos de fuga. 
2. Evaluar la retención de usuarios por cohortes. 
3. Identificar en qué paso se observa la mayor caída porcentual de usuarios y cómo varía esa pérdida por país.
4. Saber hacia qué departamentos enfocar el presupuesto y dónde ajustar el inventario.

🗣️Recomendación de negocio:
- Tomando en cuenta la etapa de select_item a add_to_cart y el fallo grave que presenta por tener la mayor caída entre ellas, se recomienda revisar la presentación de los productos así como los precios y costos de envío para evitar ése desinterés que afecta la empresa.

# Proyecto_Final_Bussines_Analytics
# Kuska Perú Travel - Turismo Receptivo: Destinos Sub Posicionados (Caso B)
 
![Logo de Kuska Perú Travel](docs/img/logo.png)
 
Kuska Perú Travel, es una agencia de turismo cuya misión es dar a conocer las maravillas ocultas del Perú y conectar las expectativas de la demanda turística con destinos regionales con alto potencial pero baja visibilidad. Sin embargo, surgen dudas del porqué son hoy gemas ocultas, no hay industria hotelera, es de difícil acceso, no hay interés, o los sitios arqueológicos no están desarrollados.
 
## Problema de negocio
 
¿En qué regiones del Perú debería Kuska Perú Travel concentrar su inversión promocional del próximo año, priorizando aquellas donde la capacidad hotelera ociosa coincide con atractivo turístico comprobado y bajas barreras de acceso o costo?
 
## Alcance actual del Proyecto
 
El proyecto ha desarrollado un EDA inicial combinando la data rescatada del Mincetur, la cual evalúa los principales indicadores de ocupabilidad mensual en las diferentes regiones del país entre 2019 y 2025. Además se exploró los datos similares de Promperú, no obstante se empleó el dataset del MINCETUR dado que Promperú trabajó con cifras anuales o mensuales sin diferenciar las regiones, lo cual complicaba el análisis. (Visualizar Anexo B)
 
Por otro lado se elaboró una encuesta para ahondar en el comportamiento de los diferentes posibles turistas y su posible apertura a adoptar nuevos destinos teniendo en cuenta las limitantes o barreras que pondrían frente a la opción de conocer destinos diferentes.
 
Todo este análisis busca responder las siguientes preguntas:
 
1. ¿Qué regiones tienen alta capacidad instalada (oferta hotelera) pero bajo flujo de visitantes?
2. ¿Qué variables explican el volumen de pernoctaciones de una región?
3. ¿Qué tipologías de destino emergen al cruzar capacidad instalada, flujo real y estancia promedio?
4. ¿Cómo se recuperó cada región tras la caída de 2020 y qué tan cerca está de su tendencia pre-pandemia?
5. ¿La intención de viaje declarada en la encuesta para las regiones "alta capacidad-bajo flujo" es consistente con la oferta hotelera real de esas regiones, o hay un desfase entre interés potencial y capacidad instalada?
Se medirán con los siguientes KPIs:
 
| KPI (Nombre Claro) | ¿Qué significa en simple? | ¿Cómo se calcula? | ¿Para qué le sirve a PROMPERÚ / Agencia? |
|---|---|---|---|
| **1. Porcentaje de Capacidad Ociosa** | El porcentaje de habitaciones de hotel que se quedan vacías cada mes. | 100% − Tasa de Ocupación | Identifica qué regiones tienen cuartos de sobra sin usar. Por ejemplo, en Cajamarca el 83% de las camas están vacías al mes (100% − 17%). |
| **2. Relación Interés vs. Ocupación** | Compara cuánta gente dice que quiere ir frente a cuánta gente realmente va. | % de personas interesadas (encuesta) ÷ % de ocupación real (MINCETUR) | Detecta "joyas desaprovechadas". Si Amazonas tiene 68% de interés en la encuesta pero solo 20% de ocupación en MINCETUR, el ratio es 3.4 (altísimo descalce que justifica hacer publicidad ya). |
| **3. Dependencia del Turismo Nacional** | Qué porcentaje de todos los visitantes que llegan son peruanos y no extranjeros. | (Arribos Nacionales ÷ Total de Arribos) × 100 | Dice a quién dirigir la publicidad. Si regiones como Huancavelica o Cajamarca tienen 98%–99% de nacionales, la campaña debe ser local/interna, no internacional. |
| **4. Grado de Recuperación Post-Pandemia** | Qué tan cerca está hoy el departamento del nivel de turistas que recibía en 2019. | (Arribos actuales [2024−2025] ÷ Arribos en 2019 [pre-covid]) × 100 | Muestra si una región está estancada o si ya rebotó, ayudando a decidir si la inversión es para "reactivar" o para "acelerar". |
| **5. Noches de Estadía por Habitación** | Cuántas noches de hospedaje se generan efectivamente por cada habitación disponible. | Total de Pernoctaciones ÷ Número de Habitaciones | Mide la rentabilidad y el movimiento económico del hospedaje: a más noches por cuarto, mayor gasto deja el turista en el destino. |
 
## Respaldo del trabajo
 
- **Carpeta con datasets:** [Google Drive](https://drive.google.com/drive/folders/1oaP0pYr8mZoDCWX68915ZwGL0ABpumW-?usp=drive_link)
- **Google Colab:** [Notebook del proyecto](https://colab.research.google.com/drive/1BQuwUZbjUqyXzoiKWywTyebogANFLUIH?usp=drive_link)
- **Encuesta:** [Formulario](https://forms.gle/NodBfNj7eSTFd4oeA)
 

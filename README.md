<p align="center">
  <img src="Logo%20de%20Kuska%20Per%C3%BA%20Travel.jpg" alt="Logo de Kuska Perú Travel" width="600">
</p>
<h1 align="center">Kuska Perú Travel</h1>
<h3 align="center">Destinos subposicionados del turismo receptivo en el Perú</h4>


<p align="center">
  Proyecto final · Caso B<br>
  Integrantes: Dayra Barboza, Isabella Castillo, Isabella Romero, Maria Fernanda Torres,Eurymar Umbria y Andrea Vera
</p>

## Resumen

Kuska Perú Travel es una agencia ficticia cuya misión es dar a conocer las maravillas ocultas del Perú. El proyecto identifica en qué departamentos conviene concentrar la inversión promocional del próximo año: aquellos con capacidad hotelera ociosa, interés real de los viajeros y barreras de acceso o costo manejables.

**Pregunta de negocio:** ¿En qué regiones del Perú debería Kuska Perú Travel concentrar su inversión promocional del próximo año, priorizando aquellas donde la capacidad hotelera ociosa coincide con atractivo turístico comprobado y bajas barreras de acceso o costo?

## Recomendación

Concentrar la inversión en **Amazonas, Ayacucho y Cajamarca**. Son los tres departamentos con mayor interés declarado en la encuesta y baja ocupación hotelera real, y se mantienen en el top 5 en el 100% de las simulaciones de pesos del score de oportunidad. La Libertad y Huancavelica completan el top 5, con menor solidez.

- **Producto:** paquetes que incluyan transporte y alojamiento, porque las barreras más mencionadas son seguridad, poca oferta de alojamiento y dificultad para llegar.
- **Alojamiento:** negociar bloqueos hoteleros o tarifas corporativas con establecimientos locales, aprovechando una capacidad ociosa superior al 80%.
- **Calendario:** lanzar preventas en enero y febrero, antes de los meses de menor demanda (abril a junio).

## Qué responde el análisis

| Pregunta | Hallazgo principal |
|---|---|
| 1. ¿Qué regiones tienen alta capacidad pero bajo flujo? | Loreto, Cajamarca, La Libertad y Lambayeque reciben menos visitantes de los que su capacidad instalada permitiría (Índice de Subposicionamiento menor a 1). |
| 2. ¿Qué variables explican las pernoctaciones? | La escala de la oferta domina: un 1% más de habitaciones se asocia a un 1.45% más de pernoctaciones. Tener sitios arqueológicos o museos, por sí solo, no explica más demanda. |
| 3. ¿Qué tipologías de destino emergen? | Cinco segmentos, desde destinos consolidados (Cusco, Lima) hasta destinos con capacidad media y flujo bajo o medio donde se concentra la oportunidad. |
| 4. ¿Cómo se recuperó cada región tras 2020? | Los departamentos más rezagados (La Libertad, Loreto, Apurímac y Ayacucho) no recuperan el nivel de 2019 en los próximos 12 meses según el pronóstico. |
| 5. ¿El interés declarado es consistente con la oferta real? | Sí. Amazonas, Cajamarca y Ayacucho combinan alto interés y baja ocupación real. |

## Datos y método

- **MINCETUR:** indicadores mensuales de ocupación hotelera por departamento, 2019 a junio 2025, calibrados con las cifras anuales oficiales.
- **Encuesta propia:** 110 respuestas válidas sobre disposición, interés y barreras de viaje.
- **Ministerio de Cultura y PROMPERÚ:** visitas a sitios arqueológicos y museos, como enriquecimiento.
- **Técnicas:** Índice de Subposicionamiento, regresión log-log, descomposición y pronóstico de series de tiempo, clustering K-Means y un score de oportunidad con análisis de sensibilidad.

Se miden cinco KPIs: capacidad ociosa, relación interés vs. ocupación, dependencia del turismo nacional, grado de recuperación post-pandemia y noches de estadía por habitación.

## Contenido del repositorio

- **Notebook:** análisis completo y reproducible, de la limpieza de datos al dashboard.
- **Dashboard interactivo:** cinco gráficos, uno por pregunta de negocio, generado con D3.
- **Informe final y presentación:** documentos de entrega.
- **Anexos:** fuentes de datos, acta de reparto, encuesta y bitácora de uso de IA.
- **Datasets:** datos originales y procesados.

## Respaldo del trabajo

- **Carpeta con datasets:** [Google Drive](https://drive.google.com/drive/folders/1oaP0pYr8mZoDCWX68915ZwGL0ABpumW-?usp=drive_link)
- **Google Colab:** [Notebook del proyecto](https://colab.research.google.com/drive/1BQuwUZbjUqyXzoiKWywTyebogANFLUIH?usp=drive_link)
- **Encuesta:** [Formulario](https://forms.gle/NodBfNj7eSTFd4oeA)

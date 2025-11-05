A Deep Learning Model for Iceberg Detection at the Amery Ice Shelf, Antarctica.

<i>This thesis was originally developed as a requirement for completing a masters degree at University College London (UCL). 
It has been assessed and awarded a Distinction grade. The written report, Google Earth Engine API code, training dataset, and model weights are available upon request. 
Redistribution or use of the following information without the author’s knowledge or citation is not permitted. </i>

Thesis Abstract:

Understanding iceberg dynamics from glacial calving is essential for improving knowledge gaps and related uncertainties in current ice mass balance estimates and climate models. Icebergs are seldom included within the workings of current methods, whilst contributing to both localised and nonlocalised freshwater influx, with the potential to alter oceanic processes through positive climate feedbacks in a warming world. To address uncertainties related to iceberg dynamics, a supervised U-Net deep learning model, using Sentinel-1 Synthetic Aperture Radar (SAR) imagery, is applied to detect icebergs in the Amery Ice Shelf (AIS) during 2015-2023. The U-Net model was trained on a large, hand-labelled dataset, irrespective of present polar features, and with minimal image preprocessing. The U-net model was evaluated against weekly-average sea ice concentration data and an advanced computational algorithm combining Otsu’s thresholding and Canny edge detection. The best model weights achieved an F1 score of 0.78 when assessed with 50 unseen samples from the AIS, identifying nearshore and offshore icebergs across a range of varying conditions, with freeboard areas as low as 5.48 km2 ± 9.6%. The model enabled the further understanding of distinct iceberg dynamics across a 1,000 km range from the AIS, whereby icebergs are grouped in relation to both their freeboard size and the dominant ocean currents present. The deep learning model poses as an effective detection method and strong alternative for iceberg detection, improving the understanding of iceberg dynamics, potentially reducing ice mass balance uncertainties, and has the potential to evolve into a reliable near-real time monitoring system.

Relevant Figures Below:


<p align="left"> <img width="600" src="https://github.com/user-attachments/assets/e8ae1849-b47f-47df-8d39-760a7e4cf470" alt="U-Net Architecture"/> </p> <p align="left"><em>U-Net architecture used for iceberg segmentation.</em></p>
<br/>

<p align="left"> <img width="600" src="https://github.com/user-attachments/assets/57355b80-5332-4886-9983-0fa6280bc97e" alt="Ice Mass Balance Parameters"/> </p> <p align="left"><em>Parameter tree showing the contribution of calving and icebergs to ice mass balance and uncertainty.</em></p>
<br/>

<p align="left"> <img width="600" src="https://github.com/user-attachments/assets/56e33a73-ed31-40b4-af47-494d7c637706" alt="Detected Icebergs"/> </p> <p align="left"><em>Example detections of icebergs by the U-Net model on unseen Sentinel-1 imagery.</em></p>
<br/>

<p align="left"> <img width="600" src="https://github.com/user-attachments/assets/6fe2efae-dce6-4818-aad4-c8af4bbd7718" alt="Geospatial and Temporal Plot"/> </p> <p align="left"><em>Temporal and geospatial distribution of detected icebergs across the Amery Ice Shelf region.</em></p>
<br/>

<p align="left"> <img width="600" src="https://github.com/user-attachments/assets/e09d85ab-0762-4f17-ab1f-28c51e2f2c6d" alt="Iceberg Grouping by Ocean Currents"/> </p> <p align="left"><em>Icebergs grouped by freeboard size and ocean current influence, suggesting a 3-group distribution model.</em></p>
<br/>



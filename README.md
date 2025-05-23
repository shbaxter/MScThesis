A Deep Learning Model for Iceberg Detection at the Amery Ice Shelf, Antarctica.

This research dissertation is submitted towards the consideration of a degree in MSc Climate Change, Department of Geography, University College London (UCL).

Thesis Abstract:
Understanding iceberg dynamics from glacial calving is essential for improving knowledge gaps and related uncertainties in current ice mass balance estimates and climate models. Icebergs are seldom included within the workings of current methods, whilst contributing to both localised and nonlocalised freshwater influx, with the potential to alter oceanic processes through positive climate feedbacks in a warming world. To address uncertainties related to iceberg dynamics, a supervised U-Net deep learning model, using Sentinel-1 Synthetic Aperture Radar (SAR) imagery, is applied to detect icebergs in the Amery Ice Shelf (AIS) during 2015-2023. The U-Net model was trained on a large, hand-labelled dataset, irrespective of present polar features, and with minimal image preprocessing. The U-net model was evaluated against weekly-average sea ice concentration data and an advanced computational algorithm combining Otsu’s thresholding and Canny edge detection. The best model weights achieved an F1 score of 0.78 when assessed with 50 unseen samples from the AIS, identifying nearshore and offshore icebergs across a range of varying conditions, with freeboard areas as low as 5.48 km2 ± 9.6%. The model enabled the further understanding of distinct iceberg dynamics across a 1,000 km range from the AIS, whereby icebergs are grouped in relation to both their freeboard size and the dominant ocean currents present. The deep learning model poses as an effective detection method and strong alternative for iceberg detection, improving the understanding of iceberg dynamics, potentially reducing ice mass balance uncertainties, and has the potential to evolve into a reliable near-real time monitoring system.

Relevant Figures Below.


<img width="420" alt="Unet_Archi" src="https://github.com/user-attachments/assets/e8ae1849-b47f-47df-8d39-760a7e4cf470" />
*U-Net architecture used in this thesis.*


<img width="1231" alt="Parameters" src="https://github.com/user-attachments/assets/57355b80-5332-4886-9983-0fa6280bc97e" />
*Parameter tree for ice mass balance (IMB) calculations, associated uncertainties, and role of calving and icebergs.*


<img width="410" alt="Detected_Icebergs" src="https://github.com/user-attachments/assets/05a0cdf8-7ca4-4e6a-9f89-e2905353a146" />
*Detected icebergs by the model on unseen data.*


![ACC_Geospatial](https://github.com/user-attachments/assets/c11e0b87-ed61-4dd0-b9dc-c5c51ef329bd)
*Geospatial and temporal plotting of icebergs from predicted model masks and geospatial coords of icebergs extracted from corresponding Sentinel-1 images.*


![ACC_Graph](https://github.com/user-attachments/assets/e09d85ab-0762-4f17-ab1f-28c51e2f2c6d)
*Graph displaying the potential 3-group distribution of icebergs from the Amery Ice Shelf, seperated by ocean currents.*

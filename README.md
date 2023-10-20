# Seismologist
Seismology has witnessed significant advancements in recent years with the application of deep learning methods to address a broad range of problems. My research group seeks to apply novel Deep Learning and Machine Learning based algorithms on seismic signals to improve Earthquake Early Warning System (EEWs) and Seismic Signal Analysis. Additionally, by implementing distinct Artificial Intelligence-driven models, High Performance Computing and supported by the statistical analysis based on classical models we are also trying to better understand the pattern associated with Seismic stress release.

## Research Position
- Independent Research Group Leader, Frankfurt Institute for Advanced Studies (FIAS), Germany (August 2020 – till date)
- Postdoctoral Researcher, Frankfurt Institute for Advanced Studies (FIAS), Germany (October 2018 – July 2020)

## Teaching Experience
- Guest Lecturer in Faculty of Geosciences and Geography, Goethe University, 60438 Frankfurt am Main

## Research Projects
### Seismic Signal Analysis using Deep Learning for single station
My team has developed an open-source Python package - **SAIPy** for fast seismic waveform data processing by implementing deep learning. SAIPy is an open-source python library where we strive to combine our previously published models into an automated pipeline for monitoring continuous seismic data so that it can be easily implemented by seismologists. It offers solutions for multiple seismological tasks such as earthquake detection, magnitude estimation, seismic phase picking, and polarity identification.


![saipy_course_cover_photo](https://github.com/srivastavaresearchgroup/srivastavaresearchgroup.github.io/assets/98320065/1f3cc16c-8d08-455c-aae2-98de9798359b)

### Earthquake Forecasting
Reliable earthquake forecasting methods have long been sought after, and so the rise of modern data science techniques raises a new question: does deep learning have the potential to learn this pattern? In this study, we leverage the large amount of earthquakes reported via good seismic station coverage in the subduction zone of Japan. We pose earthquake forecasting as a classification problem and train a Deep Learning Network to decide, whether a timeseries of length ≥ 2 years will end in an earthquake on the following day with magnitude ≥ 5 or not.


![Japan_SAPaper_Mw](https://github.com/srivastavaresearchgroup/srivastavaresearchgroup.github.io/assets/98320065/502995d0-91eb-4ee6-bb63-9dbc8681f449)

### Application of Deep Learning in HR-GNSS data

High-rate Global Navigation Satellite System (HR-GNSS) data can be highly useful for earthquake analysis as it provides continuous high-rate measurements of ground motion. This data can be used to estimate the magnitude, to assess the potential of an earthquake for generating tsunamis, and to analyze diverse parameters related to the seismic source. Particularly, in this work, we present the first results of a deep learning model based on a convolutional neural network for earthquake magnitude estimation, using HR-GNSS displacement time series. The influence of different dataset configurations, such as station numbers, epicentral distances, signal duration, and earthquake size, were analyzed to figure out how the model can be adapted to various scenarios. We explored the potential of the model for global application and compared its performance using both synthetic and real data from different seismogenic regions. The performance of our model at this stage was satisfactory in estimating earthquake magnitude from synthetic data with 0.07 ≤ RMS ≤ 0.11. Comparable results were observed in tests using synthetic data from a different tectonic region than the training data, with RMS ≤ 0.15. Furthermore, the model was tested using real data from different regions and magnitudes, resulting in a good accuracy, in the best cases with 0.09 ≤ RMS ≤ 0.33, provided that the data from a particular group of stations had similar epicentral distance constraints to those used during the model training. The robustness of the DL model can be improved to work independently from the window size of the time series and the number of stations, enabling faster estimation by the model using only near-field data. Overall, this study provides insights for the development of future DL approaches for earthquake magnitude estimation with HR-GNSS data, emphasizing the importance of proper handling and careful data selection for further model improvements.


![grafik](https://github.com/srivastavaresearchgroup/srivastavaresearchgroup.github.io/assets/98320065/90f21ed0-3c1e-467f-90c5-66af457899b9)


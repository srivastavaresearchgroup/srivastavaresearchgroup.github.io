# Seismologist
Seismology has witnessed significant advancements in recent years with the application of deep learning methods to address a broad range of problems. My research group seeks to apply novel Deep Learning and Machine Learning based algorithms on seismic signals to improve Earthquake Early Warning System (EEWs) and Seismic Signal Analysis. Additionally, by implementing distinct Artificial Intelligence-driven models, High Performance Computing and supported by the statistical analysis based on classical models we are also trying to better understand the pattern associated with Seismic stress release.

email: srivastava@fias.uni-frankfurt.de

[Linkedin](https://www.linkedin.com/in/nishtha-srivastava-82a273137/)                    [Google Scholar](https://scholar.google.co.in/citations?user=NYnFDLYAAAAJ&hl=en)               [Twitter](https://twitter.com/nishthasrivastv)
## Research Position
- Independent Research Group Leader, Frankfurt Institute for Advanced Studies (FIAS), Germany (August 2020 – till date)
- Postdoctoral Researcher, Frankfurt Institute for Advanced Studies (FIAS), Germany (October 2018 – July 2020)


## Teaching Experience
- Guest Lecturer in Faculty of Geosciences and Geography, Goethe University, 60438 Frankfurt am Main, (April 2022 – till date)
- Trained the scientist of Institute of Seismological Research (ISR) Gandhinagar and National Centre of Seismology (NCS), Ministry of Earth Sciences (MoES), New Delhi   on ‘Introduction to Deep Learning’ through an Intensive 4-day workshop at ISR (February 2023)

 ![WhatsApp Image 2023-10-22 at 08 40 26](https://github.com/srivastavaresearchgroup/srivastavaresearchgroup.github.io/assets/98320065/f015ff6d-9d97-4b8e-9c7b-425e563a4b85)
 


## Research Team


![grafik](https://github.com/srivastavaresearchgroup/srivastavaresearchgroup.github.io/assets/98320065/f0194c21-dc0d-484d-97b0-328ad773ca1c)




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

### Seismo-Volcanic event Analysis

Many active volcanoes exhibit Strombolian activity, which is typically characterized by relatively frequent mild volcanic explosions and also by rare and much more destructive major explosions and paroxysms. Detailed analyses of past major and minor events can help to understand the eruptive behavior of volcanoes and the underlying physical and chemical processes. Catalogs of these eruptions and, specifically, seismo-volcanic events may be generated using continuous seismic recordings at stations in the proximity of volcanoes. However, in many cases, the analysis of the recordings relies heavily on the manual picking of events by human experts. Recently developed Machine Learning-based approaches require large training data sets which may not be available a priori. Here, we propose an alternative user-friendly, time-saving, automated approach labelled as: the Adaptive-Window Volcanic Event Selection Analysis Module (AWESAM). This strategy of creating seismo-volcanic event catalogs consists of three main steps: 1) identification of potential volcanic events based on squared ground-velocity amplitudes, an adaptive MaxFilter, and a prominence threshold. 2) catalog consolidation by comparing and verifying the initial detections based on recordings from two different seismic stations. 3) identification and exclusion of signals from regional tectonic earthquakes. The strength of the python package is the reliable detection of very small and frequent events as well as major explosions and paroxysms. Here, we apply AWESAM to seismic data from Stromboli (Italy), Mount Etna (Italy), Yasur (Vanuatu) and Whakaari (New Zealand). We perform an inter-event time analysis to identify characteristic patterns in the events' recurrence time and the volcanic activity. We also derive a new amplitude-frequency relationship from seismo-volcanic events. With this relation, we can confirm a change in slope for large events at Stromboli, which is based on ten years of data.


![fias_article](https://github.com/srivastavaresearchgroup/srivastavaresearchgroup.github.io/assets/98320065/2a5f3319-cb65-4a41-9b0a-4b06d36e97cf)



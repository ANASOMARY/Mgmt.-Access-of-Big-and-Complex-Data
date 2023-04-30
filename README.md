# Mgmt.-Access-of-Big-and-Complex-Data
Contains files for the final project for Mgmt. Access of Big and Complex Data

Project title: Time series analysis of UFO sightings
Note: web application in this project is deployed and live on GCP, to view click this link (http://34.125.118.242:8081/)

Introduction
Unidentified Flying Object (UFO) as a topic has gained traction in recent years, and has been an intriguing “spooky” topic for years that it became part of our culture with many Hollywood movies and series about UFOs, although it is part of our culture, the subject of UFOs has been stigmatized in science communities and scientists have approached this subject with caution in fear for their careers (Dirk Schulz-Makuch) and of being called pseudo scientists or being described as tin foil hat conspiracy theorists.

Background
with the recent pentagon release of classified videos showing unidentified objects (Denise Chow and Gadi Schwartz, 2021) doing aerial maneuvers that break our physical laws and challenge the realm of what we thought possible and after the US senate formed an official committee to investigate UFO phenomenon where scientists and analysts are involved, it also became easier to study and analyze UFOs phenomenon because the data needed to do so became available and it became acceptable for legitimate news outlets to report on incidents of UFO sightings. On the other hand, the subject of UFOs with all the mysteries surrounding it is very intriguing and exciting to study given that the study was purely scientific and based on data.
For this project I will follow a scientific approach in analyzing UFO sightings data to try to draw subjective conclusions on whether UFOs are real or not and where those sightings happen, for the pure fun of it.

In summary, these are the technologies that I used and how I used them: 
1-	Built a web application using python and Dash.
2-	Created a GCP storage bucket to store web application file, dataset and LSTM.h5 model.
3-	Created a VM instance, installed python and other libraries on it, configured the firewall, copied the application file from the storage bucket through ssh and finally, deployed the web application on it.
4-	Created a Big Query dataset, and then connected it to the dataset in the storage bucket, then created 5 Big Query tables from that dataset.
5-	Used google Colab to connect to the Big Query tables and explored dataset
6-	 Within the web application I am connecting to the storage bucket and getting data from dataset as well as loading the LSTM model.


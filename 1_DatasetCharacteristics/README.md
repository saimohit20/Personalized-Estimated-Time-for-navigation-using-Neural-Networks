# Dataset Characteristics   

The dataset, presented in the technical report by Samo Rauter, Iztok Fister Jr., and Iztok Fister, comprises sport activity data collected from nine cyclists. The data was sourced from their Strava or Garmin Connect accounts and is structured in XML-based formats such as GPX or TCX. These formats include various attributes suitable for analysis, enabling diverse research in the domain of sports science, data mining, and performance analytics.

**Attributes Captured:**
- GPS location data
- Elevation
- Duration of activities
- Distance covered
- Average and maximal heart rate

**Source: Data was voluntarily contributed by cyclists, who remain anonymous for ethical reasons.**
<br></br>
## Data Conversion and Data overview 

<div align="center">
  <img src="Misc/mounting to drive.png" alt="Figure 1: Description of the image" width="900">
  <p><strong>Mounting to Drive</strong></p>
</div>
<br></br>
<div align="center">
  <img src="Misc/Preview of Data.png" alt="Figure 1: Description of the image" width="900">
  <p><strong>Preview of Data</strong></p>
</div>
<br></br>
<div align="center">
  <img src="Misc/Convert GPX to xlsx.png" alt="Figure 1: Description of the image" width="900">
  <p><strong>Converting GPX to Excel</strong></p>
</div>

#### Preprocessing data
- Deleted files recorded outside europe
- Repair currupted file
- Convert Timestamp to Seconds
<br></br>

### *Detail Information on [Colab_Notebook_Data](preprocessing.ipynb)*


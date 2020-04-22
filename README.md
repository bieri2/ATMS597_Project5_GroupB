# ATMS597_Project5_GroupB 
<b>Group members:</b> Divyansh Chug, Dongwei Fu, Carolina Bieri <br>
<b>Assigned ASOS location:</b> Des Moines, IA (Station name KDSM) <br>

<b>Goals:</b> <br>
-Train a logistic regression model to predict whether it will snow or rain <br>
-Train a TBD model to predict whether it will snow or rain <br>
-Compare models based on their performance relative to climatology (Brier skill score) <br>

<b>Repository contents:</b><br>
ATMS597_Project5_download.ipynb - Notebook to download ASOS data from FTP server. <br>
ATMS597_Project5_process.ipynb - Notebook to parse METAR in downloaded files and create one DataFrame saved as a .csv. <br>

<b>References:</b></br>
[scikit-learn Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) <br>
[Brier Skill Score calculation](https://www.statisticshowto.com/brier-score/)
[ASOS archive](https://www.ncdc.noaa.gov/data-access/land-based-station-data/land-based-datasets/automated-surface-observing-system-asos) <br>

<b>Data:</b><br>
Data were retrieved from this FTP site: ftp://ftp.ncdc.noaa.gov/pub/data/asos-fivemin/ <br>
ASOS data are available from this site at five-minute intervals. Data for station KDSM were used for this project. <br>

<b>Results summary:</b>
| Model       | Training BSS    | Validation BSS  |
| ----------- |:---------------:| ---------------:|
| Logistic Regression | TBD | TBD |
| TBD | TBD | TBD |



# Serverless Spotify Data Pipeline on AWS

Designed and implemented a serverless data pipeline on AWS to extract, transform, and analyze data from the Spotify API:


## Overview

**spotify-api-extract (Lambda funtion 1)**
- Triggered by EventBridge.
- Extracts data from the Spotify API.
- Saves raw data to an S3 bucket.

**spotify-transformation (Lambda funtion 2)**
- Triggered by the addition of new data to S3.
- Processes raw data into structured tables (album, song, artist).
- Saves processed data back to S3.



## Architecture
![](https://res.cloudinary.com/dix4vcfxa/image/upload/v1716804323/j7h5noxepvtpcus6q0qd.png)
# SAT_ACCESS
Repo to track and store progress on NOAA satellite access.

# PHASE 1:

**Goals:**
1. sat access
- Configure a RTL-SDR and necessary software suite to capture images from passing NOAA satellites. 
- Once this is successful with the factory dipole design and create a more durable and precise aluminum
  antenna and mast configuration for higher resolution. 
2. remote sat access 
- Design a yagi antenna and configure a router on the school network to broadcast my own subnet to
  the reception site on the saddle of the mountain to be able to access my home dir

**Methods:** 
- I will use a standard junk laptop with debian (blech) and the software suite and climb the mountain
  to receive images each and every time that I want to do so. 

# PHASE 2:

**Goals:** 
1. long term NOAA 15, 18 & 19 sat access
- I will create a solar powered raspberry pi satellite downlink station on the mountain running sdrpp
  server. 

2. NOAA goes sat access
- I will get permission to place a 2.4 Ghz antenna on the school roof to receive NOAAs GOES sat 
  downlink in the long term 

3. API 
- I will write an API in rust which will enable me to access the data pulled as required 
  and store it. This will entail cron-job automation of sat downlink operation and image parsing

# PHASE 3?:

**Goals:** 
1. creating a weather station at the college
- expanding the mountain satellite downlink to include a suite of weather instruments piped through 
  the same raspberry pi.
- this will entail either writing an api or finding another method to transmit the data to a local server
2. create a display in the science building for visitors and students to see live weather and most 
  recent satellite images

# Results:
<img src="https://github.com/machinehea6/SAT_ACCESS/blob/main/results/IMG_6086.jpeg?raw=true" width="80" />

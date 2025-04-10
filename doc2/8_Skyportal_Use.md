# 8. Skyportal: Creating Sources, Observation Plans and Uploading Photometry for Follow-up Advocates

## 8.1 Sources & Event Management
This section goes over what needs to be done in **SkyPortal** after you have determined an event is worth following up on. 

### **8.1.1 Create a Source**
You create a source when you decide you are following up on an event.

- **Step 1:** Navigate to the SkyPortal homepage.  
- **Step 2:** Go to Sources page. Click on the '+' sign in upper right hand corner and **"Add Source."**  
- **Step 3:** Enter the required details:
   - **Shared with**: GRANDMA (unless you've been told to share to others, as well).    
   - **Object ID:** Provided in the GCN Circular or TNS. It could be a GRB (GRBYYMMDD) or a GW event (SYYMMDD##). 
   - **Right Ascension (RA) and Declination (Dec):** Copy these values from the source information.  
- **Step 4:** Submit the source. Once added, the source will appear in the source list.

![Source Creation](media/sourcecreation.png)

**IMPORTANT:** Rarely, some GCN events automatically generate a source page. This occurs when an optical counterpart is indentified and it has been reported to the [Transient Network System (TNS)](https://www.wis-tns.org/). So, check the *sources* page to see if there are any events near T0 that could be associated with a GCN Circular or a GW alert. 

### **8.1.2 Adding Classifications**
Classifications provide clarity on the status and priority of the source. 

**Two cases when you handle classification:**

- When you have created a new source, add a classification. 

- When a new alert comes in through skyportal via email (either a GRB or GW event), check to see if a classification needs to be adjusted. Sometimes, events are labeled `Signifigant` and `GO GRANDMA` when they are not. These classifications will pop up on the header of each page and can be manually removed. You can see an example in 8.1.3.

- Scroll to the **"Classifications"** section.  
- Select:  
   - **Group:** `GRANDMA`  
   - **Taxonomy:** `GRANDMA Campaign Source Observation 1.0`  
   - Choose classification tags: `Go GRANDMA`, `Stop GRANDMA`, `Go GRANDMA (HIGH PRIORITY)`.
   - **Taxonomy:** `GRANDMA Campaign Source Classification 1.0`  
   - Choose classification tags: `Kilonova`, `Not Kilonova`, `GRB`, `Not GRB`, `GW Counterpart`, `Not GW Counterpart`, `GW Candidate`, `Not GW Candidate`, `Supernova`, `Not Supernova`, `I Care`, `Not I Care`.  
- **Probability:** Set to `1` if the classification is certain.  
- Submit your classification.

**NOTE** If observing/getting photometry after 24 hours: select `I-care`. **Short GRBs** and **Kilonvoa** are considered `GO GRANDMA (HIGH PRIORITY)`.

![SkyPortal Classification](media/classification.png)

### **8.1.3 Adding and Removing Tags**
- To **add a tag**, click on the `+` button near the tags section underneath the source name and enter your desired tag (e.g., `I Care`).  
- To **remove a tag**, hover over it and click the trash bin icon. Confirm deletion.
  
![SkyPortal Tags](media/sptags.png)

### **8.1.4 Aliases & Candidates**

Aliases is the function on skyportal where you add your candidates or associated events. So, if we have a GW event, we make source pages for the event itself and for its potential optical candidates. We, then, add any of those possible sources or optical counterparts to the GCN Event Page, as seen in the example below.

Click the '+' Symbol and add the name of the associated event as it is found in SkyPortal "Sources" tab or as the transient is named in the GCN Circular (e.g., GRB######X) and this creates a link to the [**Gamma-ray Coordinates Network Viewer**](https://heasarc.gsfc.nasa.gov/wsgi-scripts/tach/gcn_v2/tach.wsgi/?event=S250206dm).

![Aliases](media/aliasesskyportal.png)

---

## 8.2 Observability, Observation Plans and Follow-Up Requests

### 8.2.1 Observability 


### **8.2.2 Creating an Observation Plan**

Follow-Up Advocates (or Shifters) will not need to generate Observation Plans. But, it is an important aspect of SkyPortal to familiarize yourself with in the event a telescope operator requests you to generate them. 

For **GW events**, Observation Plans are generated automatically and then uploaded to **OwnCloud** in a file labeled `GWEMOPT`. 
For **GRBs**, no observation plans are automatically generated for GRBs as precise coordinates are usually provided. This means that an **OwnCloud** file needs to be created for an event to store images. 

Observation Plan generation has a few different primary features which I will go over below: 

**Select a Localization Map (blue/first arrow):**
Choose a skymap (e.g., Bilby.offline1.multiorder.fits) from a gravitational wave alert to define the sky region to target.

**Choose an Instrument (purple/second arrow):**
Select your telescope (e.g., Thai Robotic Telescope – TRT-SRO) that will perform the observations.

**Set Observation Dates (green/third arrow):**
Define the start and end times for the observation window, ensuring they align with visibility constraints and urgency.

**Set Detection Criteria (orange/fourth arrow):**
Enter the minimum number of required detections (e.g., 2) and cumulative probability coverage (e.g., 0.95) to prioritize high-confidence regions.

**Select Query List and Galaxy Catalog (light blue/fifth arrow):**
Use the sources query list and a galaxy catalog (e.g., CLU) to match potential host galaxies within the localization.

**Submit:** Press SUBMIT to generate the observation plan. The system will compute the optimal targets within your selected skymap region, date range, and detection criteria.

![Observation Plan Example](media/observationplanex.png)


### **8.2.3 Creating a Follow-Up Request**

- Go to the **"Follow-Up"** tab on the source page.  
- Select a telescope from the **GRANDMA network** (e.g., TAROT TCA, FRAM).  
- Configure observation details:  
   - **Filters**: Whether bessel or standard is specfic to the telescope and object you are viewing. See more on filters in **8.3**. 
   - **Exposure Time**  
   - **Exposure Count**  
Exposure time and count are variable. A default is usually 10 images by 300 second.
   - **Air Mass**: Use an air mass of 1.8 across all telescopes.
   - **Start and End Dates**: Do a two night range. It will give the telescope teams time to observe. 

- Submit the plan.  

### **8.2.4 Monitoring Observation Plans**
- View submitted plans on the source page.  
- Check the **Observability Map** for real-time telescope availability:  
   - **Yellow Telescopes:** Daytime  
   - **Blue Telescopes:** Nighttime  
- Prefer notifying telescopes at least two hours before nighttime.  

---

## 8.3 Uploading Photometry

Information about uploading photometry can be found in the data anlysis manual for STDWeb. However, here is some general information regarding filters within the GRANDMA system. 

Some filter systems are commonly associated with specific magnitude systems. For example:

SDSS filters (u’, g’, r’, i’, z’) are typically calibrated in the AB system.
Johnson-Cousins filters (e.g., U, B, V, R, I), also referred to as Bessel filters, are often calibrated in Vega magnitudes.
Many near-infrared filters (J, H, K from the 2MASS system) also use the Vega system.

When a counterpart is detected, use the UVOT counterpart coordinates immediately, if available. If SWIFT UVOT does not detect a counterpart, use the coordinates from other telescopes detecting the counterpart. Update to the most accurate counterpart coordinates available, even if not provided by SWIFT/UVOT.

**General guidelines:**
- Use an air mass of 1.8 across all telescopes.
- If a gain is not specified, default to a value of 1, as gains may vary slightly across telescopes. If a gain is missing in the header and causes an inspection error, consult the telescope team for the correct gain.
- If the limiting magnitude (upper limit) is unknown, make an estimated guess and leave a note. The upper limit is not typically used if a magnitude and error are provided.
- Finally, include the coordinates used in the analysis file, especially if obtained from STDWeb, the telescope team, or a GCN notice. Do not wait to add data to the table if coordinates are missing; just ensure they’re added once available.

### **8.3.1 Force Photometry with ATLAS**

- Navigate to **"Observability"** and run force photometry for archival data.  
- Recommended search windows:  
   - **Short-Term:** Last 6 days  
   - **Long-Term:** Up to 1 year  
- Analyze the data:  
   - Look for detections pre-dating the gravitational wave event.  



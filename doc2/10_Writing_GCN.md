# 10. GCN Release Protocol

A GCN (Gamma-ray Coordinates Network) Circular is released when GRANDMA has obtained images or upper limits from an alert observation. GCNs serve as a formal method of reporting GRANDMA’s observational status to the broader community.

## Who Writes the GCN?

The responsibility for drafting a GCN typically falls to:
- The **Weekly Coordinator** or
- The **scientist currently observing**.

However, if you are the FA on duty and others are unavailable, you may need to initiate or draft the GCN yourself. If images are being uploaded or observations are being processed, it’s appropriate to ask the Core Team:  
> *“Are we releasing a GCN?”*

---

## Purpose of a GCN

GCNs are used to:
- Acknowledge the **detection** of a source or **non-detection** (upper limits).
- Publicly announce GRANDMA’s **follow-up status**.
- Contribute to the **community record** of a transient.

---

## When to Release

- A GCN should be released **after the first images are obtained and reduced**, especially if upper limits can be reported.
- GCNs may summarize observations from a **single telescope** or **multiple telescopes** within the GRANDMA network.
- GCN release timing may depend on the **Core Team’s guidance** or scientific significance of the event.

---

## How to Prepare a GCN

1. **Check OwnCloud**:  
   - Navigate to the relevant alert folder under `Candidates` for a GCN draft or template.
   - You can also reference previously released GCNs within that alert's file directory.

2. **Draft Content**:
   - You may summarize results from:
     - A single GRANDMA telescope
     - A subset or the entirety of the network

3. **Templates and Examples**:  
   - Use official examples as guides:  
     - [GCN 36284](https://gcn.nasa.gov/circulars/36284?query=GRANDMA&startDate=&endDate=): single telescope, no detection  
     - [GCN 36299](https://gcn.nasa.gov/circulars/36299?query=GRANDMA&startDate=&endDate=): multi-telescope upper limits

4. **Submit via GCN Portal**:
   - Ensure formatting matches NASA GCN submission standards.
   - Include links, magnitudes, exposure details, telescope names, and full acknowledgments.

---

## Science & Publication Protocols

### In Case of **Detection**:

- The **GRB Chairs** should be consulted regarding scientific communication.
- If GRANDMA has contributed a **significant fraction of the data** (e.g., ≥50% of the planned cadence), a **GRANDMA-led paper** may be initiated.
- If GRANDMA has limited data, we may **offer data to another team’s publication**, ensuring proper credit.
- To coordinate joint publications, we are establishing points of contact with collaborations such as:
  - SVOM
  - Swift
  - Fermi
  - Colibri
  - EP

### In Case of **Non-Detection**:

- Non-detections (upper limits) may still be scientifically valuable.
- If the **upper limits are deep or numerous**, the GRB group may recommend:
  - Writing a **GCN Circular**  
  - Including the data in a **“1-per-year” backup science paper** led by GRANDMA

#### Scientific framing for upper limits may include:
- High-density environments (e.g., **faint X-ray rich GRBs**):  
  Example: [GRB 040403 (INTEGRAL)](https://arxiv.org/abs/astro-ph/0412012)
- Dust obscuration and dark GRBs:  
  - [The nature of “dark” GRBs](https://doi.org/10.1051/0004-6361/201015458)  
  - [Radio-selected dark GRBs and host dust](https://iopscience.iop.org/article/10.3847/1538-4357/ac8feb)

---

## Example GCN Text

### In Case of Detection:

**Subject:** Event Initial (GW,GRB,EP,etc) YYDDMMX GRANDMA/Kilonova Catcher Detections (if KNC data is present)

NAMES OF THE SHIFTERS on behalf of the GRANDMA (IF KNC DATA: and Kilonova-Catcher collaborations): 

The field of GRB XXX (CITE GCN OF GRB DETECTION) has been imaged with the NAME OF TELESCOPES located at NAME OF OBSERVATORY at TIME POST T0 with TYPE OF FILTER for a total exposure of PUT EXPOSURE TIME.

We detect an optical (OR NIR OR UVOT) transient at the enhanced TELESCOPE THAT DETECTED position (CITE GCN) down to (XXX FILTER) = XXX AB mag +/- XXX mag calibrated with nearby XXX stars and WITH/WITHOUT Galactic extinction correction.

(IF SEVERAL OBSERVATIONS FROM DIFFERENT TELESCOPES: PUT A TABLE WITH T-T0, RA, DEC, TELESCOPE, FILTER, MAG, EXPOSURE)

All the data have been reduced by a single data processing pipeline, STDPipe (Karpov et al., 2025 Acta Polytechnica, 65(1), 50-64). Images obtained in XXX were calibrated using the XXX catalog.

We use the SkyPortal application (skyportal.io) to monitor our observational campaign (Coughlin et al. 2023).

GRANDMA is a worldwide telescope network (grandma.ijclab.in2p3.fr) devoted to the observation of transients in the context of multi-messenger astrophysics (Antier et al. 2020 MNRAS 497, 5518).

(IF KNC DATA: Kilonova-Catcher (KNC) is the citizen science program of GRANDMA (http://kilonovacatcher.in2p3.fr/).)

---

### In Case of Non-Detection:

**Subject:** Event Initial (GW,GRB,EP,etc) YYDDMMX GRANDMA/Kilonova Catcher Observations (if KNC data is present)

NAMES OF THE SHIFTERS on behalf of the GRANDMA (IF KNC DATA: and Kilonova-Catcher collaborations):

The field of GRB XXX (CITE GCN OF GRB DETECTION) has been imaged with the NAME OF TELESCOPES located at NAME OF OBSERVATORY at TIME POST T0 with TYPE OF FILTER for a total exposure of PUT EXPOSURE TIME.

We detect an optical (OR NIR OR UVOT) transient at the enhanced TELESCOPE THAT DETECTED position (CITE GCN) down to (XXX FILTER) = XXX AB mag +/- XXX mag calibrated with nearby XXX stars and WITH/WITHOUT Galactic extinction correction.

(IF SEVERAL OBSERVATIONS FROM DIFFERENT TELESCOPES: PUT A TABLE WITH T-T0, RA, DEC, TELESCOPE, FILTER, MAG, EXPOSURE)

All the data have been reduced by a single data processing pipeline, STDPipe (Karpov et al., 2025 Acta Polytechnica, 65(1), 50-64). Images obtained in XXX were calibrated using the XXX catalog.

We use the SkyPortal application (skyportal.io) to monitor our observational campaign (Coughlin et al. 2023).

GRANDMA is a worldwide telescope network (grandma.ijclab.in2p3.fr) devoted to the observation of transients in the context of multi-messenger astrophysics (Antier et al. 2020 MNRAS 497, 5518).

(IF KNC DATA: Kilonova-Catcher (KNC) is the citizen science program of GRANDMA (http://kilonovacatcher.in2p3.fr/).)

NAMES OF THE SHIFTERS on behalf of the GRANDMA (IF KNC DATA: and Kilonova-Catcher collaborations):

The field of GRB XXX (CITE GCN OF GRB DETECTION) has been imaged with the NAME OF TELESCOPES located at NAME OF OBSERVATORY at TIME POST T0 with TYPE OF FILTER for a total exposure of PUT EXPOSURE TIME.

We do not detect any new source at the enhanced TELESCOPE THAT DETECTED position (CITE GCN) down to (XXX FILTER) < UPPER LIMIT AB mag calibrated with nearby XXX stars and WITH/WITHOUT Galactic extinction correction.

(IF SEVERAL OBSERVATIONS FROM DIFFERENT TELESCOPES: PUT A TABLE WITH T-T0, RA, DEC, TELESCOPE, FILTER, DEPTH, EXPOSURE)

All the data have been reduced by a single data processing pipeline, STDPipe (Karpov et al., 2025 Acta Polytechnica, 65(1), 50-64). Images obtained in XXX were calibrated using the XXX catalog.

We use the SkyPortal application (skyportal.io) to monitor our observational campaign (Coughlin et al. 2023).

GRANDMA is a worldwide telescope network (grandma.ijclab.in2p3.fr) devoted to the observation of transients in the context of multi-messenger astrophysics (Antier et al. 2020 MNRAS 497, 5518).

(IF KNC DATA: Kilonova-Catcher (KNC) is the citizen science program of GRANDMA (http://kilonovacatcher.in2p3.fr/).)

---
## Additional Resources

- Full archive of GRANDMA’s GCNs: [GCN Circular Database](https://gcn.nasa.gov/circulars?query=GRANDMA&startDate=&endDate=)  
- Sarah Antier's video training on GCN writing: ["Source Candidates of GW – Advice"](https://www.youtube.com/watch?v=u7M2Xhf2c5U&t=707s)  
- Transcript and guide available in **Section 7.13** of this manual

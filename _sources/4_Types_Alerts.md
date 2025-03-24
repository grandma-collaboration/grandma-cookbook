# 4. How to Respond to Different Astrophysical Alerts

## 4.1 Responding to BBH Alerts 

These alerts can be seen in #gwalerts and in SkyPortal. You follow up on these alerts with the same protocol as you do with GW alerts. Any difference is stated in its respective section. 

**A) Criteria for BBH Follow-Up**

BBH follow-up is required if any of the following conditions are met:
- **Well localized**: Sky localization area is less than 200 deg².
- **Very close**: Distance is less than 200 Mpc with a 90% credible region (CR) of less than 1000 deg².
- **Joint detection**: Counterpart detected from Neutrinos or GRBs.

**Examples**:
- BBH at 180 Mpc with a 90% CR of 50 deg²: **Yes, Follow-Up**
- BBH at 500 Mpc with a 90% CR of 100 deg²: **Yes, Follow-Up**
- BBH at 60 Mpc with a 90% CR of 4000 deg²: **No**
- BBH at 60 Mpc with a 90% CR of 4000 deg² + GRB: **Yes, Follow-Up**
- BBH at 80 Mpc with a 90% CR of 500 deg²: **Yes, Follow-Up**

**B) Determining Follow-Up Strategy**

1. **If BBH is < 200 Mpc or < 200 deg²**:
   - **Trigger All Telescopes**: Use both Tiling and Galaxy Targeting for 24 hours.
   - **Next Steps**: Trigger follow-up on counterpart candidates reported in GCN.
   - **Start Follow-Up on Candidates**: Begin as soon as they appear in GCN.
   - **Stop Follow-Up**: When it’s no longer scientifically valuable.
   - **Tags in GRANDMA**: Start and stop GRANDMA properly; don’t leave "Go GRANDMA" indefinitely.

3. **If BBH is > 200 Mpc or > 200 deg²**:
   - **Limited Follow-Up**: Use TAROT (TCH, TCA, TRE) and FRAM (Auger, CTA-N) for 24 hours.
   - **If Counterparts are Reported in GCN**: Trigger all GRANDMA telescopes.

**C) Triggering Wide Field Telescopes (TAROT, FRAM)**
- **Check Telescope Availability**: Use the GCN SkyPortal page to see which telescopes can observe.
- **Generate Plan in SkyPortal**: Be mindful of bugs (e.g., TCH) and ensure you use the most updated alert version.
- **Notify Team**: Email Sergey and Martin Masek for FRAM, Sarah Antier, and Alain Klotz for TAROT.

## 4.2 Responding to IceCube Neutrino 

These alerts will be found in GCN emails and SkyPortal (usually). 

**Criteria for Follow-Up:**

- **Energy**: High-energy neutrinos (TeV–PeV) are likely astrophysical (e.g., from supernovae, GRBs, or AGN). Low-energy neutrinos have a tendency to be atmospheric. 
- **Temporal Coincidence**: Alignment with other transient events (e.g., gamma-ray bursts or gravitational waves) suggests a multimessenger event.
- **Spatial Coincidence**: Neutrinos traced to known high-energy regions of the sky are more valuable.
- **Multiplicity**: Multiple neutrino detections from the same region indicate a strong astrophysical event.
- **Detector Sensitivity**: High signal-to-noise ratios with minimal background are more reliable.

## 4.3 Responding to Einstein Probe X-Ray Alerts 

This process is a little more vague. We are looking to see if the alert lies in the galactic plane and if there have been other high-energy phenomena detected around the time of this alert. If the galactic latitude is too low, it is a galactic event and you should pass on follow-up. Primarily, you will recieve a notice from Nicolas to follow up.

To determine if a detection is in the galactic plane, you typically evaluate the object's galactic latitude, denoted as _**b**_. The galactic coordinate system, with the center of the Milky Way at (_**l**_= 0°, _**b**_ = 0°), is used for this.

**Steps to Assess:**

1. **Galactic Coordinates**: Convert the object's equatorial coordinates (right ascension and declination) to galactic coordinates (longitude _**l**_ and latitude _**b**_). Tools like `astropy` in Python can help with this conversion.

2. **Galactic Latitude (_**b**_)**: Once you have the galactic latitude _**b**_, the closer it is to 0°, the nearer the object is to the galactic plane.
    - Objects with |_**b**_| < 5° are typically considered to be in the galactic plane.
    - Objects with |_**b**_| > 30° are generally far from the plane and are considered to be in the galactic halo or extragalactic.

Basically, if the galactic latitude _**b**_ is low (near 0°), the detection is likely in the galactic plane. For higher _**b**_, the object is outside the plane.

## 4.4 Responding to GRBs (Gamma-Ray Bursts)

When responding to GRB alerts, the following factors are crucial:

1. **Focus on GRBs reported by Swift**:
   - GRBs reported by **Swift** should be prioritized over those reported by **Fermi**, as Fermi alerts are not ingested into SkyPortal. 
   - **ZTF follow-up** nor **SkyPortal** are automated for Fermi GRBs. They should not be prioritized for follow-up.

2. **Look for Potential Counterparts**:
   - Always check if there is a potential counterpart reported by external instruments or teams.
   - If a counterpart is reported, verify the localization accuracy. 
     - If the localization is within a few arcseconds and reported by instruments like **Swift** or **SVOM**, these are high-priority alerts, and follow-up observations should be requested.

3. **Handling GRBs Without Counterparts**:
   - If no counterpart is reported for a GRB, it becomes difficult to justify observations. In these cases, asking telescopes to observe may not be productive, as there would be no clear target to point to.

4. **Source Page Activity**
   - At the start of observations, make sure to add a summary to the source page. This is the template:

   "The [Instrument/Telescope Name] triggered and located a [burst/astrophysical event] on [Date and UTC Time] (T0). Shortly after, [Follow-up Telescope/Instrument] identified an optical counterpart with a candidate located at RA=[Right Ascension], DEC=[Declination]. Approximately [Time] after T0, it was observed at [Magnitude] in the [Filter/Band]. Subsequent observations by [Observing Group/Consortium] using [Telescope(s) involved in the follow-up] detected the source approximately [Time post-T0], reaching a magnitude of [Magnitude or reporting an upper limit] in the [Filter/Band]. Observations were [noted limitations, such as affected by moonlight or poor weather conditions]."
   
   - If it has been determined, document the redshift measurement and if spectroscopy has been performed in the summary and comments. Make sure to include in the summary and update the source itself. Record the source of this information.
   - As observations continue, make sure to update the summary with who has had uploaded images, and the magnitudes/errors, and limits those images provide. Include if a candidate has been found.
   - As optical counterparts (candidates) are found, updates the coordinates on the source page accordingly. Notify #observations, skyportal comments, and your team. Make sure to include the GCN source of these coordinates. 

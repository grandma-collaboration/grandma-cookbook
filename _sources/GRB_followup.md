## Determining GRB Follow Up

### What GRBs Should Be Observed?

GRB follow-up in GRANDMA is guided by scientific interest, localization quality, and operational feasibility. GRB events are reported in the GCN Circulars. The following classes of GRBs are prioritized:

1. **Long GRBs with X-ray Counterparts**  
   - These may indicate X-ray-rich, optically faint bursts in high-density environments (possibly merger-driven).  
   - Prioritize GRBs detected in **X-rays by Swift/XRT** or similar instruments.

2. **Very Energetic GRBs**  
   - GRBs with **>10–100 GeV** emission are rare and scientifically valuable.  
   - Detected by high-energy instruments like **Fermi-LAT**.

3. **Extremely Bright GRBs (BOAT-like)**  
   - Defined by exceptionally high **peak flux** and **fluence**.  
   - Thresholds for triggering are being developed on a case-by-case basis.

4. **GRBs with Known or Estimated Redshift**  
   - **Nearby GRBs (z < 1)**: More easily detectable, may be associated with supernovae.  
   - **High-z GRBs (z > 4)**: Important for early-Universe studies.

5. **Short GRBs (T90 < 2s)**  
   - High-priority due to potential kilonova association.  
   - Often poorly localized (e.g., Fermi/GBM) — require **tiling strategies** for follow-up.

6. **Well-localized Long GRBs with Optical Counterparts**  
   - Long GRBs (T90 > 2s) with **< 5 arcmin localization uncertainty** and an optical counterpart reported by another team/instrument.

> Other scenarios, such as off-axis jets, may be considered individually by GRB chairs and the Core Team.

---

### Operational Notes on GRB Alerts

- **GRB alerts are not automatically ingested into Slack or SkyPortal** like GW alerts are.
- GRBs are **announced through GCN Circulars**, which must be monitored via email.
- **Prioritize Swift-detected GRBs**:  
  - Swift GRBs are **automatically ingested into SkyPortal**.  
  - Fermi GRBs are **not ingested** and **ZTF follow-up is not automated**, making them lower priority unless exceptional.
- If **no counterpart is reported**, observing is often unproductive. Follow-up should be reserved for events with:
  - X-ray or optical detections
  - Accurate localization
  - External team reports confirming visibility

---

### Procedure for Observing GRBs

1. **Trigger the GRANDMA Network**  
   - Share alert and relevant context via **email and Slack**.  

2. **Trigger TAROT via SkyPortal**  
   - If the GRB is **observable from TAROT** and counterpart info is promising, trigger directly.  
   - **Analyze images within ~5 hours** to evaluate detection.

3. **Stop Conditions**  
   - If **nothing is visible in the early images**, **STOP GRANDMA**.  
   - Regardless of detection, observations should **end after 2–3 days**.

4. **If Detection Occurs**  
   - **Update the RA/Dec on SkyPortal** with refined coordinates.  
   - Continue observing until the afterglow becomes **too faint for the network** (e.g., mag > 21).

5. **If External Request Is Received**  
   - If another collaboration requests follow-up with a reasonable science case,  
     the **GRB Chairs and Core Team** can approve it.  
   - In such cases, follow the standard strategy above.

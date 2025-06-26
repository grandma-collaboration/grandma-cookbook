# Responsibilities of the Shifter (FA) & Weekly Coordinator

This will provide an outline to the duties expected of the Weekly Coordinator and their Shifters. 

---
## Shifter's (Follow-Up Advocate) Responsibilities

What does "in charge of triggering and operating GRANDMA" mean? (June 2025)

- The FA is in charge of:
  - Evaluating if the GRB is interesting or not and which telescopes can be triggered. This is based on their usage frequency and capabilities (see table below).
  - Triggering the appropriate telescopes.
  - Requesting that online **measurements** (not just images in owncloud) are uploaded to **Skyportal** by the observational(telescope) teams
  - Checking results based only on GCN and internal measurements of GRANDMA in Skyportal (is it fading ?)
  - **Not analyzing images themselves** — image analysis is done by the observer or the team, or in very particular cases, by the FA's team or DAG.

- **Only measurements present in Skyportal are considered valid, not just observations.** We expect images to be analyzed and the the measurements to be uploaded 24 hours post-request for the standard case.  A professional image uploaded to Owncloud without an associated measurement in Skyportal is **not validated**.

More specifically,

- The role of the FA is not just to request observations (on Slack), but to:
  - Monitor the optical counterpart localization and its localization uncertainty (sometimes we have only a localization from gamma-ray or X-ray), and refresh this localization in SP
  - Annotate Skyportal (Which type of GRB, Group management, Feedback from observational teams, and analysis)
  - Provide, Type of source, Localization, filter, exposure, expected magnitude, AND specific time ranges of observations (e.g, within a day? within 6h? etc.)
  - Organize revisits (do not ask only one observation)
  - Monitor the expected fading rate and check consistency

When triggering an observation to an observational team, the FA must provide:

1. The most up-to-date **localization** of the GRB afterglow (in arsec uncertainties) OR **specifically state** that the localization is not precise
2. The most up-to-date **expected limiting magnitude**, based on the current light curve and measurements in Skyportal.  For this, the FA should upload all GCN measurements (as they are recieved) to Skyportal and monitor how the transient is fading.
3. The **filters** to request:
    - Default: **R** or **Johnson R**.
    - For large campaigns: consider adding **I,i** and **G,g**.
4. (Encouraged) The **number of images** and **exposure time** to request—especially when triggering via the Skyportal platform (e.g, TRT, ...).
---

Below are the different aspects of a shifter's responsibilities during their week. For links to corresponding videos, go to the bottom of this page.

### Before the Shift
- Activate your notifications to receive slack alerts for your team channel, `#observations`, and `#shifters`.
- Make sure you are recieving emails from SkyPortal and emails from the GCN Circulars
- Make sure to respond to any messages sent by your Weekly Coordinator (WC) and get their feedback.
- Start early and communicate with your team mates regarding current observations or pending data.

### At the Start of Your Shift
- Check the status of [LVK](https://online.igwn.org/grafana/public-dashboards/1a0efabe65384a7287abfcc1996e4c4d?orgld=1&refresh=5s&orgId=1). Are all instruments in operation?
- Write “on duty” in the #shifters channel on Slack.
- Perform any immediate actions requested by the previous shifter during their transmission. If no transition actions are stated, ask for a recap.
- Read the shift document. 

### During Your Shift: Regular Actions
- Check [GCN Circulars](https://gcn.nasa.gov/circulars) every 10-15 minutes and respond accordingly. 
- Update ongoing observations for GW counterpart candidate sources or GRBs (from GCN circulars) in SkyPortal with the photometry.
- If some counterpart candidate sources are found, it may be worth triggering GRANDMA, even if it is a BBH (see Section 6).
- Check observability. Contact telescope teams that have not responded to previous shifters' requests for observations. Are they observing? Have they uploaded images?
- Make sure to contact new teams at least 2 hours before their night of observations. 
- Update who is observing in the `#observations` channel and in Skyportal comments.
- Update all reporting in GRANDMA observations in sources and GCN event pages.

### In Case of a New GW or GRB Alert
- Check the status and write a report in #observations (including type of source, etc.). **NOTE:** For all **GW alerts** in #gwalerts, you need to report their name, 90/50% and distance into the observations channel. You need to say whether there is follow up or not. It is important to do this in order to make sure all alerts have been responded to and that all activity is up to date. For **GRB alerts**, make sure to include GCN #, coordinates, and source page you created.
- If there is a new alert and follow up, Add the name of the SXX in SkyPortal by going to the event page under GW/GRB/Neutrino and clicking on the ‘+’ sign at the top right (next to interactions). Add the corresponding SXX name tag to the event.
- If no follow-up is required, remove `GO GRANDMA` and add `Not-Icare` for any **GW Alerts** that are generated by SkyPortal.
- If follow-up is required, prepare to receive notifications from the telescope teams regarding their observation plans. If they don’t respond, contact them and annotate everything in the GCN event page of SkyPortal.
- Inform the next shifters about what they should track for the next 72 hours.
- Ensure that the Science READY images (calibrated images with WCS corrected) are uploaded to the corresponding folder in OwnCloud.
- Make sure the photometry values are updated in SkyPortal under sources -> click on the event link -> scroll down to Photometry -> click on ‘upload additional photometry’ and also in the OwnCloud folder.
- Make sure to update the summary as often as observations and images are uploaded.
- If observations have been made, write the circular with your team, adding all telescope teams in the author list, Follow-up advocates on duty, WC, and core team. Report a subset if there are too many observations and ensure validation from the core team.
- At the end of the process once a mag of 21, label the event `STOP GRANDMA`.

### In Case of a New GW Counterpart Candidate from GCN Circulars
- **If the source belongs to a significant GW alert**:
  - Link it with SkyPortal and add the source:
    - Go to SkyPortal Dashboard -> scroll to the bottom -> under ‘Add a Source’, choose ‘GRANDMA’ for ‘share data with’ drop-down menu. Enter the GW counterpart name given in the circular and its corresponding RA and Dec in the suggested format and click submit.
  - Add the corresponding photometry (refer to point 7 in the previous section) from the GCN circulars report.
  - Update coordinates as candidates are found. 

- **If the sources do not belong to a significant GW alert**:
  - Add it in the #icare-skyportal channel on Slack with a request to add the corresponding GCN events (can be done only by admins).
  - Check TNS ([TNS](https://www.wis-tns.org/)) and add photometry data in ‘upload photometry’ option.
  - If ZTF, check Fink ([Fink](https://fink-portal.org/)) and upload photometry data in ‘upload photometry’ option.
  - Check observability on the source page in SkyPortal and contact the appropriate telescope teams via the SkyPortal follow-up request drop-down menu (scroll to the bottom).
  - Annotate the report in SkyPortal during the 3 days in the GCN-GW event page under ‘interactions/social’.
  - Ensure Science READY images (calibrated images with WCS corrected, bias, and flat in fits) are uploaded.
  - Make sure the photometry values are updated in SkyPortal under sources -> click on the event link -> scroll down to Photometry -> click on ‘upload additional photometry’ and also in the OwnCloud folder.
  - Write the corresponding circular.
  - After 3 days, label the event STOP GRANDMA.

### At the End of your Daily Shift

**UPDATE THE SHIFT DOCUMENT. UPDATE THE SKYPORTAL COMMENTS.**

Communication between FAs and the weekly coordinator is crucial. We encourage frequent communication not only with the WC but also with other FAs. The weekly coordinator (WC) will create a Slack channel for your group.

If you need help with shift work or scheduling, seek assistance within your team first before contacting Cristina or another core team member. 

At the end of each shift, you need to list your activities: 
- If we are observing: which telescopes did you last contact?
- What was the last GCN you checked?
- Did you add photometry to skyportal from a GCN?
- Who uploaded images? 

If you notice that the previous shifter did not complete all tasks, it is YOUR responsibility to fill the gap and ensure tasks are not left incomplete. It is also courteous to inform the FA of any uncompleted tasks. Accidents happen!

Here are some examples of communication between FAs. 

**Note:** As an FA, remember to annotate all events with new circulars coming in SkyPortal.

## Weekly Coordinator Checklist

Weekly Coordinators (WCs) lead the week of shifts and are expected to make sure that their Shifter's are following their responsibilities and reaching out for support when needed. 

### Communication & Readiness

- [ ] Make sure **Operation: Shifts** spreadsheet and **SkyPortal** are up to date for accurate communication between shifts.
- [ ] Check that each shifter has access to necessary utilities and are trained. Report to Cristina if training is needed. 
- [ ] Reach out to shifters at the **start of the week** to confirm their preparation.
- [ ] Be available as the **first point of contact** for shifter questions and technical issues.


### Shift Oversight

- [ ] Confirm that **shifters are logging all actions properly** in the shift log document (Section 11).
- [ ] Ensure **SkyPortal is updated** with (Section 9):
  - Source summaries
  - Photometry
  - Comments on decisions or activity
- [ ] Review **GCN entries** and check that key GCNs are added to the appropriate tables in the log document (Section 11).
- [ ] Verify that **all image data is uploaded** to OwnCloud and processed or flagged for review (Section 9 & 11).
- [ ] Cross-check that any **follow-up requests** (e.g., GO GRANDMA, STOP GRANDMA) were issued and recorded (Section 9).

### Decision Authority

- [ ] Make **final decisions** on whether to observe events that shifters are unsure about.
- [ ] Coordinate with the Core Team and relevant science leads as needed.


## Shifter & Weekly Coordinator Responsibility Videos

For an overview on the FA's responsibilities and the use of skyportal, see this [video](https://www.youtube.com/watch?v=_N7fgiPfiXA). The transcript can be found in Section 12: Transcripts. 

If you are new to GRANDMA and would like to better understand your role within the collaboration, Sarah has made helpful videos explaining them:

- **FAs:** [Video Explanation](https://www.youtube.com/watch?v=3LtLRkEGx0w)

- All instructions and tutorials can be found here: [FA Instructions](https://forge.in2p3.fr/projects/grandma/wiki/FAinstruction_)

For both weekly coordinators and FAs, you can find videos below to help you subscribe to a shift of your preference. The videos have transcripts in Section 12 of this document.

- **Weekly Coordinators:**
  - Instructions for non-European time zones: [Video](https://www.youtube.com/watch?v=LPvvChG1Lg8)
  - Instructions for European time zones: [Video](https://www.youtube.com/watch?v=9L1OJ77OI_I)

- **FAs:**
  - Instructions on how to subscribe to shifts: [Video](https://www.youtube.com/watch?v=0QNlvaGl7XY)

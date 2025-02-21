# 9. Shifter’s Checklist

Below are the different aspects of a shifter's responsibilities during their week. For links to corresponding videos, go to the bottom of this page.

## 9.1 Before the Shift
- Activate your notifications to receive source and GCN GW events notifications on your phone or other devices.
- Make sure to respond to any messages sent by your Weekly Coordinator (WC) and get their feedback.

## 9.2 At the Start of Your Shift
- Check the status of [LVK](https://online.igwn.org/grafana/public-dashboards/1a0efabe65384a7287abfcc1996e4c4d?orgld=1&refresh=5s&orgId=1). Are all instruments in operation?
- Write “on duty” in the #shifters channel on Slack.
- Perform any immediate actions requested by the previous shifter during their transmission. If no transition actions are stated, ask for a recap.

## 9.3 During Your Shift: Regular Actions
- Check [GCN Circulars](https://gcn.nasa.gov/circulars) every 30 minutes and annotate all GCN GW event social pages in SkyPortal. You can also query SkyPortal to pick up the circular easily under the properties tab by updating GCN circulars at the bottom of the page.
- Update ongoing GW counterpart candidate sources (from GCN circulars) in SkyPortal with the photometry, whether or not we are observing them with GRANDMA.
- If some counterpart candidate sources are found, it may be worth triggering GRANDMA, even if it is a BBH (see Section 9.5).
- Contact telescope teams that have not responded to previous shifters' requests for observations. Contact new teams 2 hours before their night of observations. Update who is observing in the #observations channel and in Skyportal comments.
- Update all reporting in GRANDMA observations in sources and GCN event pages.

## 9.4 In Case of a New GW Alert
- Check the status and write a report in #observations (including type of source, etc.). **NOTE:** For all GW alerts in #gwalerts, you need to report their name, 90/50% and distance into the observations channel. You need to say whether there is follow up or not. It is important to do this in order to make sure all alerts have been responded to and that all activity is up to date. 
- If there is a new alert and follow up, Add the name of the SXX in SkyPortal by going to the event page under GW/GRB/Neutrino and clicking on the ‘+’ sign at the top right (next to interactions). Add the corresponding SXX name tag to the event.
- If no follow-up is required, remove GO GRANDMA and add Not-Icare.
- If follow-up is required, prepare to receive notifications from the telescope teams regarding their observation plans. If they don’t respond, contact them and annotate everything in the GCN event page of SkyPortal.
- Inform the next shifters about what they should track for the next 72 hours.
- Ensure that the Science READY images (calibrated images with WCS corrected) are uploaded to the corresponding folder in OwnCloud.
- Make sure the photometry values are updated in SkyPortal under sources -> click on the event link -> scroll down to Photometry -> click on ‘upload additional photometry’ and also in the OwnCloud folder.
- Make sure to update the summary as often as observations and images are uploaded.
- Write the circular with your team, adding all telescope teams in the author list, Follow-up advocates on duty, WC, and core team. Report a subset if there are too many observations and ensure validation from the core team.
- At the end of the process, label the event STOP GRANDMA.

## 9.5 In Case of a New GW Counterpart Candidate from GCN Circulars
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

## 9.6 At the End of your Daily Shift

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

### 9.6.1 LogBook Template & Examples

This template is not strictly mandatory, but it is recommended to follow these parameters when communicating shift to shift and team to team. Ensure you are constantly checking for active observations, not just the new ones that occurred during your shifts.

**Template:**

**Date:** DD-MM-YYYY  
**On duty:** “Your Name/Weekly Coordinator’s Name” on duty “your shift slot” UTC

**Events of Shift Here**

(or if an alert has been detected:)

**New alert:** “name of alert”  
**Parameters:** “list of parameters”; Observation Plan?; Go-GRANDMA?;

**Instrument:** (observation plan or not, performed? Why?)  
For the ones who are not in night time: **NIGHT:** “when night time occurs

--- Example for when there was an alert during your shift (Flag also the data analysis) ---

25-5-2023
Cristina Andrade/Vini Rupchandani on duty 22h-04h UTC

New alert: GW candidate S230525a
Parameters: NSBH, -90% area: 1001.0 deg2 / 50% area: 266.0
-Distance: 276.0 +/- 79.0 Mpc, GRANDMA Score: 2, GO-GRANDMA. 
Contacted the following people: X, X, X, X. These are the ones who have responded.
UBAI-T60N: No Observation Plan.
ShAO-T60: Received Observation Plan. Unable to Observe due to probability is 0.0005.
Abastumani-T70: Received Observation Plan

--- Example for a week with a candidate search ---

**Previous FA to the Next FA**

- **New Events:**
  - `S230601bf`: BBH far away, significant (annotation on SkyPortal done but labelization is missing; you need to take care of it), waiting for interesting transients
- **GCN Tracker:**
  - Keep track of GCN circulars > 33903
- **Further Events:**
  - `S2329ay`: Source candidate from ZTF (GCN33900): ZTF23aapmnpce needs to be labelized correctly once photometric data have been imported
  - `AT2023`: Source candidate is observing with KAO, waiting for improved weather in ShAO. No response from the UBAI team regarding observations
- **Technical Issue:**
  - `S230601bf` didn't produce any #gwalerts notifications; Sarah will capture this

## 9.7 At the End of Your Shift Week
- Check the status of [LVK](https://online.igwn.org/grafana/public-dashboards/1a0efabe65384a7287abfcc1996e4c4d?orgld=1&refresh=5s&orgId=1). Include status in report. 
- Present positives and negatives for the next FA team.
- Provide a report of the observations made and results.

## 9.8 Shifter & Weekly Coordinator Responsibility Videos

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

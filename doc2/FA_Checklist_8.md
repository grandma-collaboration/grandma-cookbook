# 8. Shifter’s Checklist

## 8.1 Before the Shift
- Activate your notifications to receive source and GCN GW events notifications on your phone or other devices.
- Make sure to respond to any messages sent by your Weekly Coordinator (WC) and get their feedback.

## 8.2 At the Start of Your Shift
- Check the status of [LVK](https://online.igwn.org/grafana/public-dashboards/1a0efabe65384a7287abfcc1996e4c4d?orgld=1&refresh=5s&orgId=1).
- Write “on duty” in the #shifters channel on Slack.
- Perform any immediate actions requested by the previous shifter during their transmission. If no transition actions are stated, ask for a recap.

## 8.3 During Your Shift: Regular Actions
- Check [GCN Circulars](https://gcn.nasa.gov/circulars) every 30 minutes and annotate all GCN GW event social pages in SkyPortal. You can also query SkyPortal to pick up the circular easily under the properties tab by updating GCN circulars at the bottom of the page.
- Update ongoing GW counterpart candidate sources (from GCN circulars) in SkyPortal with the photometry, whether or not we are observing them with GRANDMA.
- If some counterpart candidate sources are found, it may be worth triggering GRANDMA, even if it is a BBH (see Section 8.5).
- Contact telescope teams that have not responded to previous shifters' requests for observations. Contact new teams 2 hours before their night of observations. Update who is observing in the #observations channel and in Skyportal comments.
- Update all reporting in GRANDMA observations in sources and GCN event pages.

## 8.4 In Case of a New GW Alert
- Check the status and write a report in #observations (including type of source, etc.).
- Add the name of the SXX in SkyPortal by going to the event page under GW/GRB/Neutrino and clicking on the ‘+’ sign at the top right (next to interactions). Add the corresponding SXX name tag to the event.
- If no follow-up is required, remove GO GRANDMA and add Not-Icare.
- If follow-up is required, prepare to receive notifications from the telescope teams regarding their observation plans. If they don’t respond, contact them and annotate everything in the GCN event page of SkyPortal.
- Inform the next shifters about what they should track for the next 72 hours.
- Ensure that the Science READY images (calibrated images with WCS corrected) are uploaded to the corresponding folder in OwnCloud.
- Make sure the photometry values are updated in SkyPortal under sources -> click on the event link -> scroll down to Photometry -> click on ‘upload additional photometry’ and also in the OwnCloud folder.
- Write the circular with your team, adding all telescope teams in the author list, Follow-up advocates on duty, WC, and core team. Report a subset if there are too many observations and ensure validation from the core team.
- At the end of the process, label the event STOP GRANDMA.

## 8.5 In Case of a New GW Counterpart Candidate from GCN Circulars
- **If the source belongs to a significant GW alert**:
  - Link it with SkyPortal and add the source:
    - Go to SkyPortal Dashboard -> scroll to the bottom -> under ‘Add a Source’, choose ‘GRANDMA’ for ‘share data with’ drop-down menu. Enter the GW counterpart name given in the circular and its corresponding RA and Dec in the suggested format and click submit.
  - Add the corresponding photometry (refer to point 7 in the previous section) from the GCN circulars report.

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

## 8.6 At the End of Your Shift Week
- Check the status of [LVK](https://online.igwn.org/grafana/public-dashboards/1a0efabe65384a7287abfcc1996e4c4d?orgld=1&refresh=5s&orgId=1). Include status in report. 
- Present positives and negatives for the next FA team.
- Provide a report of the observations made and results.
- Fill out the Overleaf summary report.

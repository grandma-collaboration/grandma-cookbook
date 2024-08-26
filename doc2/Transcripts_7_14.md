### 7.14 Responding to Gravitational Wave Alerts: Follow-Up Advocate

**(Introduction):**

Hello, for those who do not know me. I am Cristina Andrade, a GRANDMA core team member. 
In this video, I’ll cover how to read and respond to the various types of Gravitational-Wave alerts. 
I’ll break down the process into manageable sections and provide detailed instructions for each step. 
Feel free to send your questions to the zoom chat or the #training channel. An experienced team member can respond in the interim or I will respond at the break between sections. 

**(Section 1: Getting Started)**

Please make sure you are signed up for Owncloud, SkyPortal and FORGE. You can find the information on connecting in the manual under Section 1 “Signing Up for GRANDMA’s Utilities”

I am going to briefly go over the correct settings you should see in order to be receiving alerts from SkyPortal. 

We will use SkyPortal in our observational campaigns. This platform serves as our interface for conducting the campaign, including receiving alerts, contacting teams, updating data, etc.

Upon connecting, you'll encounter a page similar to the one shown below (if not, click on Dashboard in the left sidebar). Your initials should appear in the top right corner.

To correctly set up your profile in SkyPortal, you need to adjust your profile settings to activate the notifications you wish to receive.

 As Follow-Up Advocates (FAs), you'll need to access your profile to modify your notification preferences.

For Follow-Up Advocates:

When making any setting changes, press update after each line.

Make sure you have turned on the "Sources" button and select GW CANDIDATE and GW COUNTERPART from the list of options.

Click Update!

Below "sources," find the "GCN Events" option. Ensure to activate this option and then click "create new profile."

Your GCN Events profile should include: LVC_PRELIMINARY, LVC_INITIAL, LVC_UPDATE, LVC_RETRACTION under "GCN Notice Types" and GW under "GCN Tags," as shown below:

Make sure to press update. 

In all cases, make sure to configure options to receive alerts via email and Slack by clicking on the "bell" symbol.

Make sure to select on shift as this will guarantee notifications while you have signed up as a shifter. 

For information on how to turn these settings on in Skyportal, you can go to the manual under Section 1.5, “Connecting to ICARE Skyportal” or find this video in the GRANDMA youtube channel. 

For Slack notification instructions, check under Section 1.2 or just google “how to turn on notifications for specific slack channels”.

I will pause here for questions. The next section will discuss how to understand the different GW alert types. 

**(Section 2: Understanding GW Alert Types)**

While you are on shift, you are going to be checking the status of the #gwalerts channel on slack often.
I recommend once every ~15 minutes to ensure prompt response. 
As soon as a new GW trigger is received, the #gwalerts channel will have a new entry. At the time of an alert, you will receive an email AS SHOWN ON THE LEFT or see a message in the #gwalerts channel as shown on the right. Read the entry. 
You are going to see one of four different types of alerts: early, preliminary, initial, and update.
The first you’ll receive for a new detection is a PRELIMINARY alert. 
In GRANDMA, we initially respond to the PRELIMINARY alert. This is the first type of alert you will receive when an event is detected by LVK (LIGO - VIRGO - KAGRA).  
PRELIMINARY alerts have a SKYMAP associated with it. This is what GRANDMA uses to point our telescopes.
You can find this skymap and other relevant information pertaining to the alert by clicking on the link found in the #gwalerts channel. This will take you to the gracedb.ligo.org page for this detection. 
Here you can see what the time of the alert was. If you scroll down to “Log Messages”, you can find the PRELIMINARY sky map. This sky map was released alongside the first preliminary alert. 
The gravitational-wave experts at LVK also receive the PRELIMINARY alert and they are woken up to understand whether or not it comes from an astrophysical event or it is just noise. 
I’ll talk more about noise later. 
The PRELIMINARY alert arrives when LVK interferometers have made a detection and the systems on LVK are processing the information. 
The INITIAL alert is the next type of alert to arrive after the PRELIMINARY. 
Initial:
INITIAL alerts can arrive within an hour of the preliminary to several hours later. Sometimes, an INITIAL alert  is not sent to the community or is never received by GRANDMA. 
As well, in the event that the alert is not astrophysical (a false alert), you will receive a retraction.
The next type of alert to arrive after the INITIAL is the UPDATE. 
Update:
After several hours to one day, we receive an UPDATE alert for the same event. 
The INITIAL and UPDATE alert are important to monitor because it will constrict the skymap of the GW source. 
Only some events will have a PRELIMINARY, INITIAL AND UPDATE alerts. Not all of the
events will. 
As a shifter, you need to read all of the alerts that arrive during your shift, whether you have received the PRELIMINARY alerts during your shift time or not. This is why it is important to make accurate reports between shift times."
SIDE NOTE:  "Rarely, before the PRELIMINARY, an EARLY warning alert will be delivered. We do not follow up in GRANDMA with these EARLY alerts because there is no skymap associated with it. These are not things you need to respond to. Wait for the PRELIMINARY alert. ”
Sarah describes the different alert types in more detail in her video “GW alert: different types”. The transcript for this video can be found in Section 7.8 of the manual. 
Now, we know what the various types of alerts we can receive during our shift time will look like. 

I will pause here for questions. The next section will go over what to do when we receive a new preliminary alert. 

**(Section 3: We received a new PRELIMINARY alert!)**

When you receive a new PRELIMINARY alert, Check the properties of the alert in the @gwalerts channel. Then, write a report in the #observations channel; specifying the type and quality of the alert. 
This will allow the wider collaboration to be notified of an event and prepare. 
This report will include the following: 
What is the name of the alert? 
Is it a BBH,BHNS, BNS? 
What is its Distance? 
What is the area?
Do we Follow - Up? 
And if we do follow-up, or “GO-GRANDMA”, we need to tag the whole channel. “@channel” 

When reading a preliminary alert, we need to understand its quality in order to correctly respond to the “Follow-Up?” question. 

 GRANDMA focuses on alerts originating from BNS and BHNS, located relatively nearby—below 200 Mpc—and within an area below 200 deg^2, with a GRANDMA score of 2 or 3. These are the properties you will primarily look at to determine follow-up. 

SIDE NOTE: There are two other properties to keep in mind when determining follow-up for detections that may not score high but have other good properties.
Check Trigger Time and Time since T0 in the #gwalerts message. If "Time since T0” is above one day, it means that we don't care about it. 

The second, Coherence between detectors vs noise, we need to see the value. When it is below negative three, it means that there is a high chance that the event is not astrophysical and is a mistake or just noise. 

These are the secondary properties you will weigh when the distance, area and GRANDMA score are not in perfect conditions. 

 If all the primary requirements are met, you can request follow-up observation by submitting the report and including “GO-GRANDMA” in the message you send to #observations. 

This means you are notifying telescopes to begin observing.

If the alert does not meet these criteria, you respond with NO FOLLOW UP.

When this tag happens, no email needs to be sent and no mention in skyportal.

These are example reports for alerts of different types and significance: 
Example 1 is a good alert:
New GW alert: S230525a, NSBH, Distance: 276.0 +/- 79.0 Mpc, GRANDMA Score: 2, GO-GRANDMA. @channel
Example 2 is an alert that is not of interest to GRANDMA: 
New GW Alert: S231231ag, BBH, distance 1114 +/- 357 Mpc, no follow up.
Example 3 occurs after you receive an initial alert or an update that clarifies it is no longer worth following up on. For example, it is no longer a BNS or NSBH. 
No new observations. Tagged alert GW230525 with “BBH” and “Not I-care”. Removed “GO-GRANDMA”. 

You include this information in your end of shift report. I will discuss end of shift reports in more detail at a later time but they are similar to what you send in observations. 

Make note that sometimes new PRELIMINARY alerts can come in between UPDATE or INITIAL alerts for another detection. It is possible that you will be managing several different alerts at the same time.

Sarah describes this in more detail in her video, “Preliminary alert slack message”. This video should have already been viewed by the FAs, as she discusses important nuances that help FAs determine follow-up. 

The transcripts for that video are in Section 8.3. A summary of that information is also found in the manual under Section 3.

I will pause here for questions. The next section will go over what to do after you post in the #observations channel. 

**(Section 4: “GO GRANDMA”)**

If it is a good quality alert and you have sent out requests for follow-up observations, these are your next steps. 

 Add the name of the event, for example, “S231231ag” in Skyportal, by accessing the menu bar and going to ‘Sources’. This is not automatically done. 

 Make sure it is tagged “I-care” and “GO  GRANDMA”  by selecting  the "+" symbol on the Skyportal interface. This informs anyone viewing Skyportal that we are currently observing this detection. 

To note, after a follow-up worthy PRELIMINARY alert is sent out, GRANDMA will automatically generate an observation plan. 
Telescope teams will be able to retrieve these plans from owncloud or Skyportal.
 
As telescope teams respond to you in #observations, enter who is and is not observing and why, in the comments section of SkyPortal; include the telescope name, who responded to you, and if they cannot observe…include why. 

SIDE NOTE:  The telescope teams must conduct observations within 24 hours of receiving the plan. If they do not, no further observations are required.

So, make sure to accurately update Skyportal from information in #observations and when posting to the comment section on skyportal.

Update the event accordingly as you receive more alerts about the object: 

 If the source does not meet follow up specifications, you can remove the tag “GO GRANDMA” and add the tag "Not I-care". You can remove tags by hovering over them and selecting the trash symbol. 

To sum it up, IF it is follow up worthy, you tag “I-care” and “GO GRANDMA”. 

If it does not, remove GO GRANDMA and add “Not I-care”. 

Furthermore and the last step, if you have initiated observations, upon confirmation from the core team that we are stopping all observations, remove the “GO GRANDMA" tag and add "STOP GRANDMA" with the +. Make a short announcement in #observations and include it in your end of shift report.  

I will pause here for questions. The next section will go over what to do after you’ve requested observations and the subject of GW counterpart candidates. 

Section 5: Responding to New GW Counterpart Candidates from GCN Circulars

So far, we have reviewed the different types of alerts, what makes a detection worth following up on, how to request observations, and learned where to document which telescopes have confirmed their ability to observe. 

Now, we will discuss what the protocol is in the case that we get to observe a GW counterpart candidate.

Due to this process of observation following a PRELIMINARY alert that we previously discussed, potential candidates for the optical counterpart can be identified. These are what we refer to as GW source candidates. 

We have a 72-hour window which needs to begin in the first 24 hours following the PRELIMINARY alert. Then, we can search for GW source candidates within the subsequent 72 hours for both types of observation plans (including Galaxy targeting and tiling).

As telescope teams are observing and uploading images of the GW source candidates, FA’s will be doing the following. These will be expanded on in another video and in the manual soon:

 linking significant GW alerts with Skyportal and adding corresponding sources by checking GCN circulars that you should be receiving in your email, TNS and Fink for additional data. 

You’ll be adding photometry data from GCN circulars as they are uploaded to owncloud.

For sources not belonging to significant GW alerts, notify admins to add corresponding GCN events in #icare-skyportal channel.

You’ll be assessing observability in SkyPortal and contacting relevant telescope teams. 
Annotating reports in SkyPortal for 3 days.

Ensuring Science READY images and photometry values are updated.

For more information on GW Source Candidates and different types of observation plans, please refer to Sarah’s video, “GW source candidates - Transients (follow-up advocate)”. As well, the transcript for this video can be found in Section 7.7. 

Next Section is End of Shift Reports and what they look like. 

**(Section 6: End of Shift Report)**
The end of shift reports are pretty straight forward and do not need to follow an exact format. Examples of a template with a list of telescopes do exist in the manual under Section 4.1, in case you ever need a reminder. 
However, end of shift reports do need to include the following, if applicable: name of new alert that occurred during your shift, updates for any previous alerts that were followed up on, telescope teams you contacted, the most recent GCN circulars that occurred during your shift, and any activities in skyportal (such as did you update any tables, comments, candidates, or GCNs on skyportal).
NOTE: If any of these are not applicable to what occurred during your shift time. For example, if there were no new alerts, state “No new alerts.” 
Like I stated before, they should look like what you send in #observations for an alert. 
These are example reports for alerts of different types and significance: 
Example 1 is a good alert:
New GW alert: S230525a, NSBH, GRANDMA Score: 2, GO-GRANDMA, waiting for responses from telescope teams. The following telescopes have responded: XX, YY, ZZ. Created skyportal source for it. Comments have been updated. 
Example 2 
1 New GW Alert: S231231ag, BBH, distance 1114 +/- 357 Mpc, no follow up.
Example 3 
No new alerts, Last GCN #####, updated skyportal comments for S230525a. Checked photometry for {insert telescope here}.

**(Conclusion):**

As we conclude this video, remember to follow these steps diligently for effective follow-up actions. 
As well, during your shift, make sure to read all alerts in the #gwalerts channel as it is possible for parameters to change and a detection to become worthy or unworthy of follow up. 
If you have any questions or encounter difficulties, don't hesitate to reach out for assistance. 
Thank you for your attention, and let's continue our efforts to contribute meaningfully to our observations in O4b. 

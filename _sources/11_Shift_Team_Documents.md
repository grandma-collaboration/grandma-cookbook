# 11. Shift Team Logs: Importance and Best Practices

### Why Are Shift Logs Essential?

Shift logs are the **backbone of continuity and coordination** during observational campaigns. They provide:
- A **clear record** of what was done during a shift.
- A **hand-off point** for the next shifter to know what to follow up on.
- Documentation for **GCN writing**, publications, and pipeline troubleshooting.
- A full historical archive for **evaluating observational coverage**, identifying gaps, or reconstructing science cases.

> **If it's not written down, it didn't happen.**
---
Below is a template of what should be included in a shift log to monitor observations *as a team*. Particularly, we create these documents using google docs, due to its versatility. 

## 11.1 Structure of a Shift Log Document

Each shift entry should follow a standardized structure and be written directly in the **Team Shift Document** under the correct date and UTC range.

### Template for Shift Entry
The end of each shift should include the following, when appropriate. 

**Shift X – [Date] UTC [Start Time]–[End Time] ([Shifter Name])**

**1. General**
- Notable observations or alerts
- Any decisions made (e.g., STOP GRANDMA, new trigger)

**2. Telescope Contacts**
- Telescopes contacted
- Method of contact (Slack/email)
- Response received (Yes/No/Observed)

**3. Image Status**
- Images received
- Images uploaded to OwnCloud 
- Photometry performed (Yes/No)
- Uploaded to SkyPortal (Yes/No)

**4. GCN Activity**
- GCNs added to SkyPortal
- New GCNs that came in during the shift
- Drafted/published GCNs (link if possible)

**5. Comments & To-Dos**
- Issues encountered (weather, response delays, data problems)
- Tasks for next shifter
- Any `STOP GRANDMA` decisions with justification

## 11.2 Keeping Track of Observation Campaigns, Images, & GCN Circulars 

For busy weeks with any ongoing observations, especially when there is more than one (e.g., GRB250221A, GRB250226A), create individual subtabs in the shift google document for each event. This helps:
- Isolate activity by target
- Track telescope responses and data uploads per source
- Organize summary tables, comments, and plans

### 11.2.1 Subtab: Images Table
For each event, include a table tracking image activity:
| # | Image Name |   | STDweb Link | Uploaded to SkyPortal (Y/N) |   |   |
|---|------------|---|-------------|------------------------------|---|---|
|   |            |   |             |                              |   |   |

### 11.2.2 Subtab: GCN Table 
| GCN # | Related Event | Instrument | Type (Photometry/Redshift/Localization) | Uploaded to SP (Y/N) |
|-------|----------------|------------|------------------------------------------|------------------------|
| 39417 | GRB250221A     | TAROT      | Detection                                | Y                      |
| 39429 | EP250223a      | EP         | Localization                             | N                      |

### Subtab: GCN Drafts
You can also include a seperate tab to draft GCN Circulars of GRANDMA observations. This makes collaboration easy. 

---
**IMPORTANT:** You can also find an example of an actual team's shift log [here](https://docs.google.com/document/d/11tXXEBVkPFeMdqQbqNmF4IC55_eCqX42GmtsI9qbx-M/edit?usp=sharing). 

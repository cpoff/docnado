title:      Event Workflow
desc:       How to create, publish, and manage events.
date:       2020/11/24
template:   document
version:    1.0.0
nav:        PAG/RTA Docs>Events>Event Workflow
authors:    curt.poff@gmail.com
--------------------------------------
---

## Create event in Outlook Calendar

- Create a new event. Best to use the Office 365 version of Outlook in a web browser.
- Select site calendar(s) where you want the event to appear. Three to choose from: PAG-Main, RTA-Main (includes RTA & RTAnext), or PAG/RTA-Shared (appears on both sites)
- Add standard date, start/end times, reminder (optional)
- Add only internal attendees (e.g. committee chair) and no external attendees. (External attendees will be added later, after the event is fully produced.)
- Reserve conference room, or select Virtual
- Go into Response Options, select Hide Attendee List&#42; and Allow Forwarding. Leave Request Responses unchecked for virtual meetings and checked if we host the meeting at PAG. 
- Send

*The Hide Attendee List is only available using Outlook in Office 365. So you'll need to edit the event using a web browser.
{: .tip}

That creates your new meeting/event without making it visible to the public. At this point everything is still private.

## Approvals {#approvals}

Two things require approvals: the associated documents, and the meeting itself. 

- Sheila will deliver approved documents through a separate workflow, and those docs should be attached to the meeting in Outlook. Documents require specific naming convention. [See below](#document-naming-convention)

- Approval for the meeting as a whole (the final go-ahead) will also come from Sheila. Once approval is given, go into the event in Outlook and add the <b style="color:green;">Green category</b>. 

The sole purpose of the <b style="color:green;">Green</b> category is to indicate status, with <b style="color:green;">Green</b> being equivalent to LIVE. If it's <b style="color:green;">Green</b>, it's eligible to be viewed by the public. That's why the category should only be added once past the approvals threshold. Without the <b style="color:green;">Green</b> category it's not eligible and will not appear on the public calendars. There shouldn't be any need to change the category once the docs & event are approved and set to <b style="color:green;">Green</b>.
{: .info}

After <b style="color:green;">Green</b> has been applied, you can start adding <b>external attendees</b>. They will get a copy of the meeting invitation via e-mail along with all subsequent updates to the Outlook event. Make sure you only add them once the event has been fully built, edited, and approved. Attendees get every subsequent update to the meeting/event invitation in Outlook, no matter how minor. So make sure you have 100% sign off on the original pre-event invitation as it is intended to be the only communication sent via Outlook.

The website version of the event will be an exact mirror of the Outlook event pulled automatically via API that has front-end logic looking specifically for items in the <b style="color:green;">Green</b> category that are no more than **7 days** in the future. 

## Document naming convention {#document-naming-convention}
COMMITTEE ACRONYM YYYY-MM-DD TITLE OF CONTENTS.pdf

No punctuation is allowed except dash (`-`) and underscore (`_`). No exceptions.
{: .warning}

Examples:<br>
RTACAC YYYY-MM-DD Safety Subelements Handout.pdf<br>
RTATMC YYYY-MM-DD Agenda.pdf<br>
RTACART YYYY-MM-DD Legal Actions.pdf<br>
RTABoard YYYY-MM-DD Item_5A Project Delivery Status Report.pdf<br>
POPTECH YYYY-MM-DD Meeting Minutes.pdf<br>
PAGTIPSUB YYYY-MM-DD Presentation_1 Slides That Were Shown.pdf

## Public calendars

What calendars appears on each site:

**PAG**: : PAG-Main, PAG/RTA-Shared<br>
**RTA**: RTA-Main, PAG/RTA-Shared<br>
**RTA Next**: RTA-Main, PAG/RTA-Shared

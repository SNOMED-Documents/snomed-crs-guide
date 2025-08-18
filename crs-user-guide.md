# CRS Quickstart User Guide

## What is the SNOMED CT Content Request Service (CRS)?

This tool allows users to request modify or make additions to SNOMED CT.

## How do I get to CRS?

Please go to [https://request.ihtsdotools.org](https://request.ihtsdotools.org) or [http://snomed.org/crs](http://snomed.org/crs), where you will be asked to log in.

## How do I obtain a CRS Account?

Please see, [accessing-crs.md](accessing-crs.md "mention").

## Is there any quick introduction?

Yes. (_and the screen is purposefully blank for a few minutes.._)

{% embed url="https://youtu.be/-bR_wL8Rwjk" %}

## What type of content requests can I make?

Before making any request, please read the guidance on submitting content -

[Version 15.0 Customer Guidance for Requesting Changes to SNOMED CT 20240723.pdf](attachments/22318960/245794146.pdf)

Users are able to create requests to add, modify or retire information in SNOMED CT, including:

* Creating a new Concept(s)
* New Synonym(s)
* Add Parent(s)
* Modify Description(s)
* Modify Parent(s)
* Modify Relationship(s)
* New Relationship(s)
* Retire Concept(s)
* Retire Description(s)
* Retire Relationship(s)
* Other:
  * Request for new attributes to be introduced
  * Request for existing attributes to be removed
  * Request for existing Refsets to be amended (new members or changes)
  * Request for enhancement (clean-up) of areas of SNOMED CT
  * Request for changes to the concept model
  * Changes to editorial policy statements
  * Changes to text definitions (e.g. "surgical procedure")
  * Request for Quality initiative to address specific quality issues within the Terminology

## How are Requests Prioritized?

All requests are treated as normal priority with the exception of data errors. Where a request points towards a possible error in SNOMED CT, the request will be prioritized for investigation.

## How do I submit a request?

There are two methods of creating requests for SNOMED Content: [create-a-request-in-simple-mode.md](creating-requests/create-a-request-in-simple-mode.md "mention") and [create-a-batch-request.md](creating-requests/create-a-batch-request.md "mention"). To learn more about these modes and help choosing the correct one see: [creating-requests](creating-requests/ "mention").

## Can I save my Content Request and return to it later for completion?

Users may exit the system for later completion, validation, and submission.

## Can I modify my Request once it is submitted?

As an requester you can do a number of things on each request - [managing-submitted-requests-screen.md](managing-submitted-requests-screen.md "mention").

## Request Status Glossary

| CRS Status               | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | PreviousSIRS Status              |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- |
| **Draft**                | A request that has been started and saved but not yet submitted.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | _Draft_                          |
| **New**                  | All submissions (excluding draft) are initially assigned a status of New. A preliminary check will be carried out to ensure that the new request falls within the inclusion criteria and scope for the International Edition of SNOMED CT before the request will be progressed.                                                                                                                                                                                                                                                                                                                                                                                                                         | _New_                            |
| **Accepted**             | Following initial review, each request is assigned to a member of the Content Team. A change to a status of ‘Accepted’ does not mean that the request will be approved for inclusion in SNOMED CT.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | _Approved_ _& Accepted In Scope_ |
| **Under Authoring**      | A member of the Content Team is actively evaluating the request.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | _Construction_                   |
| **In Inception**         | Where a new request aligns with an ongoing content project, the request will be placed into this status until editorial policy is available to support the requested change or addition. Content projects are intended to investigate issues or enhancements to both existing and future content for SNOMED CT. A process for understanding the problem and elaboration of a solution is undertaken in order to make improvements to existing content and clarify how content of a similar nature will be incorporated into SNOMED CT in the future. Depending upon the nature of the content project, this may be a longterm large-scale content project or a smaller project with a shorter timescale. | _Awaiting policy_                |
| **Clarification Needed** | Where insufficient information is provided to proceed with a request, a member of the Content Team will incorporate questions to be resolved and change the status of the request to ‘Clarification Needed’. This will generate an email to the original requester. Where a request for clarification to a customer is not answered within **60 days** from the date the clarification is generated, the request will be marked as rejected.                                                                                                                                                                                                                                                             | _Clarification requested_        |
| **Forwarded**            | Where a request is received that is not in scope for the International Edition of SNOMED CT, it may be suitable for a specific extension. The request may be marked as forwarded to denote that it has been handed over to another extension manager or National Release Center.                                                                                                                                                                                                                                                                                                                                                                                                                         | _Forwarded_                      |
| **Withdrawn**            | Once submitted, a request cannot be deleted but can be "Withdrawn" by the original requestor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | _Withdrawn_                      |
| **In Appeal**            | Where a request has been “Not Accepted”, the submitter may request a further review of the decision. The submitter can then place the request in “In Appeal” status. In these circumstances the decision will be reviewed and if necessary referred to the Head of Terminology for final disposition.                                                                                                                                                                                                                                                                                                                                                                                                    | _Appeal_                         |
| **Appeal Rejected**      | After conclusion of the appropriate appeal process, where the outcome remains unchanged, this status will be applied.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | _Appeal Rejected_                |
| **Rejected**             | Where a request has had a full review and is not considered to be in scope for SNOMED CT, or does not meet the criteria outlined in the Editorial Guide, or clarification about the request has not been received within 60 days it will be rejected.                                                                                                                                                                                                                                                                                                                                                                                                                                                    | _Rejected_                       |
| **Ready For Release**    | The requested change has been made and approved, however this status does not assure that the requested change will be included in the final release data.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | _Construction_                   |
| **Completed**            | A request status will be changed to "Completed" once the SNOMED CT International Edition, in which the request has been addressed, has been released.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | _Completed_                      |

***

## **Further Information**

* [Getting Started](Getting-Started_28744206.html)
* [New Features & Improvements - January 2017](35987303.html)
* [Accessing CRS](Accessing-CRS_29952273.html)
* [Navigating CRS from the Sidebar](Navigating-CRS-from-the-Sidebar_28744036.html)
* [Creating Requests](Creating-Requests_29955993.html)
* [What happens after my request is submitted?](31033247.html)
* [Managing Submitted Requests Screen](Managing-Submitted-Requests-Screen_28743005.html)
* [Reassign Request](Reassign-Request_28744028.html)
* [Notifications](Notifications_28743010.html)
* [Withdrawing a Submitted Request](Withdrawing-a-Submitted-Request_31033092.html)
* [End to End Work Flow - Simple Mode](End-to-End-Work-Flow---Simple-Mode_31033033.html)
* [CRS Workflow](CRS-Workflow_31033237.html)
* [Content Request Glossary](Content-Request-Glossary_31033266.html)
* [Displaced Comment (internal only)](31983487.html)
* [Demonstration Videos](Demonstration-Videos_31985089.html)
* [SIRS to CRS Status Map](SIRS-to-CRS-Status-Map_31985160.html)
* [My CRS Reports](My-CRS-Reports_28741199.html)
* [Printable Version](Printable-Version_31985764.html)
* [Customizing the list view screen](Customizing-the-list-view-screen_35988558.html)
* [Batch Template Changes](Batch-Template-Changes_129127343.html)

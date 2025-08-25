# US CRS User Guide

<figure><img src="../images/50597960.png" alt=""><figcaption><p>What is the US SNOMED CT Content Request Service (USCRS)?</p></figcaption></figure>

This tool allows users to request, modify, or make additions to SNOMED CT. The USCRS is the SNOMED International content request system specific for user content requests for the US Edition of SNOMED CT.

The USCRS tool is important in the effort to support the development, enhancement, and distribution of clinically specific vocabularies to facilitate the exchange of clinical data and improve retrieval of health information. SNOMED CT is one of a suite of designated standards for use in U.S. Federal Government systems for the electronic exchange of clinical health information and is also a required standard in interoperability specifications of the U.S. Healthcare Information Technology Standards Panel.

## How do I get to USCRS?

Please go to [US Edition SNOMED CT Content Request System](https://us-request.ihtsdotools.org/) ([https://us-request.ihtsdotools.org/](https://us-request.ihtsdotools.org/)), where you will be asked to log in.

**Please Note:** The application is optimized for the Google Chrome browser - please do NOT use another browser (such as IE).

## How do I obtain a USCRS Account?

If you already have an account to access [IHTSDO Confluence](https://confluence.ihtsdotools.org/), you will be able to access CRS with your existing account credentials, although you will still need to request access to be able to log in to CRS.

If you do not have an account, or find that you do not have access, please fill in the following form to request access: [Confluence User Accounts](https://confluence.ihtsdotools.org/display/ILS/Confluence+User+Accounts). Under 'Why do you need a Confluence account' please indicate that it is to submit USCRS requests and click the appropriate box in the next section.

Should you still have any difficulty, please contact us by sending an email to [uscrs@snomed.org](mailto:uscrs@snomed.org).

Once logged in through IMS, you are automatically logged in to the USCRS. Choose the USCRS from the list of IHTSDO tools and you will be redirected to your USCRS dashboard.

Additional information can be found on the SNOMED International [Accessing CRS](../Accessing-CRS_29952273.html) page.

## Is there any quick introduction?

Yes. (_and the screen is purposefully blank for a few minutes.._)

{% embed url="https://www.youtube.com/watch?v=rASf0c_nJtk" %}

## What type of content requests can I make?

Before making any request, please read the guidance on submitting content -

[Users able to create requests to add, modify or retire information in SNOMED CT including:](../download/attachments/47688628/Version%2014.0%20Customer%20Guidance%20for%20Requesting%20Changes%20to%20SNOMED%20CT%2020240226.pdf)

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

There are three methods of creating requests for SNOMED Content: Simple Mode, Direct Mode, and Batch Mode. To learn more about these modes and help choosing the correct one see: Creating Requests.

A basic understanding of SNOMED CT content and structure is required, and each request must include a justification, or practical use case. Every request must also include an identifier that links to the current version of either International Edition of SNOMED CT or US Edition of SNOMED CT. Both [International and US Editions](https://www.nlm.nih.gov/healthit/snomedct/us_edition.html) are available from the National Library of Medicine to users with a UMLS Metathesaurus License.

## Can I save my Content Request and return to it later for completion?

Users may exist the system for later completion, validation, and submission.

## Can I modify my Request once it is submitted?

As an requestor you can do a number of things on each request - Managing Submitted Requests Screen

## Request Status Glossary

<table><thead><tr><th width="120.31640625">CRS Status</th><th width="466.734375">Description</th><th>Previous SIRS Status</th></tr></thead><tbody><tr><td><strong>Draft</strong></td><td>A request that has been started and saved but not yet submitted.</td><td><em>Draft</em></td></tr><tr><td><strong>New</strong></td><td>All submissions (excluding draft) are initially assigned a status of New. A preliminary check will be carried out to ensure that the new request falls within the inclusion criteria and scope for the International Edition of SNOMED CT before the request will be progressed.</td><td><em>New</em></td></tr><tr><td><strong>Accepted</strong></td><td>Following initial review, each request is assigned to a member of the Content Team. A change to a status of ‘Accepted’ does not mean that the request will be approved for inclusion in SNOMED CT.</td><td><em>Approved</em> <em>&#x26; Accepted In Scope</em></td></tr><tr><td><strong>Under Authoring</strong></td><td>A member of the Content Team is actively evaluating the request.</td><td><em>Construction</em></td></tr><tr><td><strong>In Inception</strong></td><td>Where a new request aligns with an ongoing content project, the request will be placed into this status until editorial policy is available to support the requested change or addition. Content projects are intended to investigate issues or enhancements to both existing and future content for SNOMED CT. A process for understanding the problem and elaboration of a solution is undertaken in order to make improvements to existing content and clarify how content of a similar nature will be incorporated into SNOMED CT in the future. Depending upon the nature of the content project, this may be a longterm large-scale content project or a smaller project with a shorter timescale.</td><td><em>Awaiting policy</em></td></tr><tr><td><strong>Clarification Needed</strong></td><td>Where insufficient information is provided to proceed with a request, a member of the Content Team will incorporate questions to be resolved and change the status of the request to ‘Clarification Needed’. This will generate an email to the original requester. Where a request for clarification to a customer is not answered within <strong>60 days</strong> from the date the clarification is generated, the request will be marked as rejected.</td><td><em>Clarification requested</em></td></tr><tr><td><strong>Forwarded</strong></td><td>Where a request is received that is not in scope for the International Edition of SNOMED CT, it may be suitable for a specific extension. The request may be marked as forwarded to denote that it has been handed over to another extension manager or National Release Center.</td><td><em>Forwarded</em></td></tr><tr><td><strong>Withdrawn</strong></td><td>Once submitted, a request cannot be deleted but can be "Withdrawn" by the original requestor.</td><td><em>Withdrawn</em></td></tr><tr><td><strong>In Appeal</strong></td><td>Where a request has been “Not Accepted”, the submitter may request a further review of the decision. The submitter can then place the request in “In Appeal” status. In these circumstances the decision will be reviewed and if necessary referred to the Head of Terminology for final disposition.</td><td><em>Appeal</em></td></tr><tr><td><strong>Appeal Rejected</strong></td><td>After conclusion of the appropriate appeal process, where the outcome remains unchanged, this status will be applied.</td><td><em>Appeal Rejected</em></td></tr><tr><td><strong>Rejected</strong></td><td>Where a request has had a full review and is not considered to be in scope for SNOMED CT, or does not meet the criteria outlined in the Editorial Guide, or clarification about the request has not been received within 60 days it will be rejected.</td><td><em>Rejected</em></td></tr><tr><td><strong>Ready For Release</strong></td><td>The requested change has been made and approved, however this status does not assure that the requested change will be included in the final release data.</td><td><em>Construction</em></td></tr><tr><td><strong>Completed</strong></td><td>A request status will be changed to "Completed" once the SNOMED CT International Edition, in which the request has been addressed, has been released.</td><td><em>Completed</em></td></tr></tbody></table>

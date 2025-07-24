# Batch Template Changes

The information on this page covers the updated version of the Batch Template available in the next release of both the International CRS and the US CRS from 02 Sep 2021. The current template will no longer work from that date onwards, although if used, you will receive a warning message to indicate this.

As part of ongoing development and maintenance, the batch template has been updated. The current batch template has been in use since the use of the previous content request systems (SIRS) and an update to align with new processes and systems has been overdue. Most changes in the template have aligned the template to the fields used in the current Content Requests as part of  [<figure><img src="https://jira.ihtsdotools.org/secure/viewavatar?size=xsmall&avatarId=10410&avatarType=issuetype" alt="" title=""><figcaption><p>The new batch templates can be downloaded from:</p></figcaption></figure>CRS-688](https://jira.ihtsdotools.org/browse/CRS-688?src=confmacro) \- Improve Bulk import Closed .

International CRS| [CRS_Batch_Template-2021.xls](https://confluence.ihtsdotools.org/download/attachments/27594472/CRS_Batch_Template-2021.xls?version=3&modificationDate=1629900576000&api=v2)  
---|---  
US CRS| [USCRS_Batch_Template-2021.xls](https://confluence.ihtsdotools.org/download/attachments/27594472/USCRS_Batch_Template-2021.xls?version=4&modificationDate=1629900677000&api=v2)  
  
## Changes

In most cases, any changes are additive, so you will be able to copy & paste any content from the older template into the new ones attached here.

  

Template Tab| Changes  
---|---  
New Concept| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Marked "**Definition** " as an optional field
  * Marked "**Proposed Use** " as required field
  *  _Removed column "Justification"_

**Note:**

  * If no Summary is provided in the template, then the FSN will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
New Synonym| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then [concept Id] and [proposed description] will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Add Parent| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then [concept id] Is A [destination concept id] will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Change Description| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then the new Term will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Change Parent| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then "Move [concept id] to parent [destination concept id]" will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Change Relationship| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then the relationship id will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
New Relationship| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then "[concept id] [relationship type] [destination concept id]" will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Retire Concept| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then the concept id will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Retire Description| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then the description id will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Retire Relationship| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then the relationship id will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests

  
Other| 

  * Added column "**Summary** "
  * Added column "**Reference** "
  * Renamed column "Justification" to "**Proposed Use** "

**Note:**

  * If no Summary is provided in the template, then the request description will be used to populate the Summary field in requests
  * If no Reference is provided in the template, then "Proposed Use" will be used to populate the Reference field in requests


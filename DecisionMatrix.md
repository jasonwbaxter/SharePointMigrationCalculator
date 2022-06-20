# Migration Decision Matrix

## What functionality do you require:

|What functionality do you require?|--|
|--|--|
|New site Desktop experience|N
|New site Desktop & Mobile experience|Y
|Connected experience with MS Teams|N
|Existing Site as is|Y

---
## Who will be the owner / Business decision Maker:

|Decision|Owner|Justification|Renewal Date|
|---|---|---|---|
|To Migrate|Adele Vance|Some business reason....|2022-06-23|
|Re-affirm Governance|____|____|2022-06-25|
|Don't Migrate| no ownership| no justification|2022-08-31|

---


## Modernization Approaches:

|Classic to modern|Method |Alternate Method|
|--|--|--|
|Pages|Migrate to classic and Run PowerShell| Rebuild|
Documents and information| Migrate with Migration Tool|Apply Permissions|
Workflows |Rebuild|Rebuild
Permissions|Permissions Matrix|Cross check with Business owner & Apply|
InfoPath|Migrate to classic and re-setup connections|Rebuild in PowerApps.

### Pages Appendix
|Tooling|Source|Destination|Feature|Status|
|---|---|---|---|---|
SPMT|Site Pages|Classic pages|Publishing Features|x|
ShareGate|Site Pages|Classic pages|Publishing Features|:)|
SPMT|Site Pages|Modern pages|Publishing Features|x|
ShareGate|Site Pages|Modern pages|Publishing Features|x|
SPMT|Pages|Modern pages|Wiki / Web part|:)|
ShareGate|Pages|Modern pages|Wiki / Web part|:)|
|

>Note: Pages cannot migrate without a content type / page layout associated with each page.
---


##  Size of Data considerations


|Size|Number of Site Collections|Migration Time Required|Testing Time required|Cut Over Wave|
|---|---|---|---|---|
|100GB|2|


## Testing Plan's

|#| Test Plan Name|Description|Steps|Time to Complete|
|---|---|---|---|---|
|1| OOTB Test|Tests out of the box functionality|6|30min per site|
|2| Search||||||
|3|Office online Server|Preview's





# base\_currency

Data structure that contains information about a report suite's base currency settings.

|Element|Type|Description|
|-------|----|-----------|
|**base\_currency** |`xsd:string` | Three-letter currency code \(for example, USD\). |
|**base\_currency\_test** |`xsd:string` | A user friendly name associated with the currency code. |
|**in\_queue** |`xsd:int` | Flag that indicates whether the item is in the Pending Approval queue. Supported values include: `1`: In the Pending Approval queue. `0`: Not in the Pending Approval queue. **Note:** Populated in method response only. Leave `in_queue` blank for method requests. |
|**status** |`xsd:int` | If `in_queue = 0`, then `status = 0`. If `in_queue = 1`, status is one of the following values: `1`: Pending approval to Save. `2`: Pending approval to Delete. **Note:** Populated in method response only. Leave `status` blank for method requests. |

**Parent topic:** [Data Types](../data_types/c_datatypes.md)

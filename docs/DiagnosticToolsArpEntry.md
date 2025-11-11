# DiagnosticToolsArpEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | [**DiagnosticToolsArpEntryAddress**](DiagnosticToolsArpEntryAddress.md) |  | [optional] 
**all_entry** | **bool** | All IPv4 addresses | [optional] 
**interface_name** | **str** | Interface Name | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_arp_entry import DiagnosticToolsArpEntry

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsArpEntry from a JSON string
diagnostic_tools_arp_entry_instance = DiagnosticToolsArpEntry.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsArpEntry.to_json())

# convert the object into a dict
diagnostic_tools_arp_entry_dict = diagnostic_tools_arp_entry_instance.to_dict()
# create an instance of DiagnosticToolsArpEntry from a dict
diagnostic_tools_arp_entry_from_dict = DiagnosticToolsArpEntry.from_dict(diagnostic_tools_arp_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



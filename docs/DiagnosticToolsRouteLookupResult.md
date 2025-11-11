# DiagnosticToolsRouteLookupResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nexthop_address** | **str** | IPv4 or IPv6 gateway address (required) | [optional] 
**outgoing_interface** | **str** | Interface name (required) | [optional] 
**prefix** | **str** | IPv4 or IPv6 longest matching prefix (required) | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_route_lookup_result import DiagnosticToolsRouteLookupResult

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsRouteLookupResult from a JSON string
diagnostic_tools_route_lookup_result_instance = DiagnosticToolsRouteLookupResult.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsRouteLookupResult.to_json())

# convert the object into a dict
diagnostic_tools_route_lookup_result_dict = diagnostic_tools_route_lookup_result_instance.to_dict()
# create an instance of DiagnosticToolsRouteLookupResult from a dict
diagnostic_tools_route_lookup_result_from_dict = DiagnosticToolsRouteLookupResult.from_dict(diagnostic_tools_route_lookup_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



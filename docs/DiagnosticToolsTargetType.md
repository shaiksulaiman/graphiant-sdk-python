# DiagnosticToolsTargetType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interface** | **str** | Source Interface name | [optional] 
**vrf_name** | **str** | Configured VRF Name | [optional] 

## Example

```python
from graphiant_sdk.models.diagnostic_tools_target_type import DiagnosticToolsTargetType

# TODO update the JSON string below
json = "{}"
# create an instance of DiagnosticToolsTargetType from a JSON string
diagnostic_tools_target_type_instance = DiagnosticToolsTargetType.from_json(json)
# print the JSON string representation of the object
print(DiagnosticToolsTargetType.to_json())

# convert the object into a dict
diagnostic_tools_target_type_dict = diagnostic_tools_target_type_instance.to_dict()
# create an instance of DiagnosticToolsTargetType from a dict
diagnostic_tools_target_type_from_dict = DiagnosticToolsTargetType.from_dict(diagnostic_tools_target_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



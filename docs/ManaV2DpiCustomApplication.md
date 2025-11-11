# ManaV2DpiCustomApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**destination_network** | **str** |  | [optional] 
**destination_network_list** | **str** |  | [optional] 
**destination_port** | **int** |  | [optional] 
**destination_port_list** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**ip_protocol** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**source_network** | **str** |  | [optional] 
**source_network_list** | **str** |  | [optional] 
**source_port** | **int** |  | [optional] 
**source_port_list** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_dpi_custom_application import ManaV2DpiCustomApplication

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2DpiCustomApplication from a JSON string
mana_v2_dpi_custom_application_instance = ManaV2DpiCustomApplication.from_json(json)
# print the JSON string representation of the object
print(ManaV2DpiCustomApplication.to_json())

# convert the object into a dict
mana_v2_dpi_custom_application_dict = mana_v2_dpi_custom_application_instance.to_dict()
# create an instance of ManaV2DpiCustomApplication from a dict
mana_v2_dpi_custom_application_from_dict = ManaV2DpiCustomApplication.from_dict(mana_v2_dpi_custom_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



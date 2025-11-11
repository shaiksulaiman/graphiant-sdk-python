# V1DevicesInventoryPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_serial** | **str** |  | [optional] 
**uuid** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_inventory_post_response_data import V1DevicesInventoryPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesInventoryPostResponseData from a JSON string
v1_devices_inventory_post_response_data_instance = V1DevicesInventoryPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V1DevicesInventoryPostResponseData.to_json())

# convert the object into a dict
v1_devices_inventory_post_response_data_dict = v1_devices_inventory_post_response_data_instance.to_dict()
# create an instance of V1DevicesInventoryPostResponseData from a dict
v1_devices_inventory_post_response_data_from_dict = V1DevicesInventoryPostResponseData.from_dict(v1_devices_inventory_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



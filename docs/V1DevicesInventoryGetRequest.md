# V1DevicesInventoryGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**not_assigned** | **bool** |  | [optional] 
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_inventory_get_request import V1DevicesInventoryGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesInventoryGetRequest from a JSON string
v1_devices_inventory_get_request_instance = V1DevicesInventoryGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesInventoryGetRequest.to_json())

# convert the object into a dict
v1_devices_inventory_get_request_dict = v1_devices_inventory_get_request_instance.to_dict()
# create an instance of V1DevicesInventoryGetRequest from a dict
v1_devices_inventory_get_request_from_dict = V1DevicesInventoryGetRequest.from_dict(v1_devices_inventory_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesInventoryClearReturnPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_serials** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_inventory_clear_return_post_request import V1DevicesInventoryClearReturnPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesInventoryClearReturnPostRequest from a JSON string
v1_devices_inventory_clear_return_post_request_instance = V1DevicesInventoryClearReturnPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesInventoryClearReturnPostRequest.to_json())

# convert the object into a dict
v1_devices_inventory_clear_return_post_request_dict = v1_devices_inventory_clear_return_post_request_instance.to_dict()
# create an instance of V1DevicesInventoryClearReturnPostRequest from a dict
v1_devices_inventory_clear_return_post_request_from_dict = V1DevicesInventoryClearReturnPostRequest.from_dict(v1_devices_inventory_clear_return_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



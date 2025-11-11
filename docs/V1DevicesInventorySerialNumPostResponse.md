# V1DevicesInventorySerialNumPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inventory** | [**List[OnboardingHardwareInventory]**](OnboardingHardwareInventory.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_inventory_serial_num_post_response import V1DevicesInventorySerialNumPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesInventorySerialNumPostResponse from a JSON string
v1_devices_inventory_serial_num_post_response_instance = V1DevicesInventorySerialNumPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesInventorySerialNumPostResponse.to_json())

# convert the object into a dict
v1_devices_inventory_serial_num_post_response_dict = v1_devices_inventory_serial_num_post_response_instance.to_dict()
# create an instance of V1DevicesInventorySerialNumPostResponse from a dict
v1_devices_inventory_serial_num_post_response_from_dict = V1DevicesInventorySerialNumPostResponse.from_dict(v1_devices_inventory_serial_num_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



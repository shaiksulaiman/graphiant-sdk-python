# V1DevicesUpgradeCancelPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_ids** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_upgrade_cancel_put_request import V1DevicesUpgradeCancelPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesUpgradeCancelPutRequest from a JSON string
v1_devices_upgrade_cancel_put_request_instance = V1DevicesUpgradeCancelPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1DevicesUpgradeCancelPutRequest.to_json())

# convert the object into a dict
v1_devices_upgrade_cancel_put_request_dict = v1_devices_upgrade_cancel_put_request_instance.to_dict()
# create an instance of V1DevicesUpgradeCancelPutRequest from a dict
v1_devices_upgrade_cancel_put_request_from_dict = V1DevicesUpgradeCancelPutRequest.from_dict(v1_devices_upgrade_cancel_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



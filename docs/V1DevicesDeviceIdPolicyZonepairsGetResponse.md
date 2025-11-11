# V1DevicesDeviceIdPolicyZonepairsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**zone_pairs** | [**List[ManaV2FirewallZonePair]**](ManaV2FirewallZonePair.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_policy_zonepairs_get_response import V1DevicesDeviceIdPolicyZonepairsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdPolicyZonepairsGetResponse from a JSON string
v1_devices_device_id_policy_zonepairs_get_response_instance = V1DevicesDeviceIdPolicyZonepairsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdPolicyZonepairsGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_policy_zonepairs_get_response_dict = v1_devices_device_id_policy_zonepairs_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdPolicyZonepairsGetResponse from a dict
v1_devices_device_id_policy_zonepairs_get_response_from_dict = V1DevicesDeviceIdPolicyZonepairsGetResponse.from_dict(v1_devices_device_id_policy_zonepairs_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



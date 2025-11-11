# V1GlobalSnmpsDeviceGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**snmps** | [**List[ManaV2Snmp]**](ManaV2Snmp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_snmps_device_get_response import V1GlobalSnmpsDeviceGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSnmpsDeviceGetResponse from a JSON string
v1_global_snmps_device_get_response_instance = V1GlobalSnmpsDeviceGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSnmpsDeviceGetResponse.to_json())

# convert the object into a dict
v1_global_snmps_device_get_response_dict = v1_global_snmps_device_get_response_instance.to_dict()
# create an instance of V1GlobalSnmpsDeviceGetResponse from a dict
v1_global_snmps_device_get_response_from_dict = V1GlobalSnmpsDeviceGetResponse.from_dict(v1_global_snmps_device_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



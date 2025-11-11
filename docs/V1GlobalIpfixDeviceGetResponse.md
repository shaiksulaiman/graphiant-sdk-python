# V1GlobalIpfixDeviceGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**exporters** | [**List[ManaV2IpfixExporter]**](ManaV2IpfixExporter.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_ipfix_device_get_response import V1GlobalIpfixDeviceGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalIpfixDeviceGetResponse from a JSON string
v1_global_ipfix_device_get_response_instance = V1GlobalIpfixDeviceGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalIpfixDeviceGetResponse.to_json())

# convert the object into a dict
v1_global_ipfix_device_get_response_dict = v1_global_ipfix_device_get_response_instance.to_dict()
# create an instance of V1GlobalIpfixDeviceGetResponse from a dict
v1_global_ipfix_device_get_response_from_dict = V1GlobalIpfixDeviceGetResponse.from_dict(v1_global_ipfix_device_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



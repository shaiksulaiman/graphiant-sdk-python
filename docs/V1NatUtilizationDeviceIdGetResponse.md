# V1NatUtilizationDeviceIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nat_usage** | [**IpfixNatUsage**](IpfixNatUsage.md) |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_nat_utilization_device_id_get_response import V1NatUtilizationDeviceIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1NatUtilizationDeviceIdGetResponse from a JSON string
v1_nat_utilization_device_id_get_response_instance = V1NatUtilizationDeviceIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1NatUtilizationDeviceIdGetResponse.to_json())

# convert the object into a dict
v1_nat_utilization_device_id_get_response_dict = v1_nat_utilization_device_id_get_response_instance.to_dict()
# create an instance of V1NatUtilizationDeviceIdGetResponse from a dict
v1_nat_utilization_device_id_get_response_from_dict = V1NatUtilizationDeviceIdGetResponse.from_dict(v1_nat_utilization_device_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



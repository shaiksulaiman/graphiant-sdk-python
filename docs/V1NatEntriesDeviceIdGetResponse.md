# V1NatEntriesDeviceIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nat_entries** | [**List[IpfixNatEntry]**](IpfixNatEntry.md) |  | [optional] 
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_nat_entries_device_id_get_response import V1NatEntriesDeviceIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1NatEntriesDeviceIdGetResponse from a JSON string
v1_nat_entries_device_id_get_response_instance = V1NatEntriesDeviceIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1NatEntriesDeviceIdGetResponse.to_json())

# convert the object into a dict
v1_nat_entries_device_id_get_response_dict = v1_nat_entries_device_id_get_response_instance.to_dict()
# create an instance of V1NatEntriesDeviceIdGetResponse from a dict
v1_nat_entries_device_id_get_response_from_dict = V1NatEntriesDeviceIdGetResponse.from_dict(v1_nat_entries_device_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



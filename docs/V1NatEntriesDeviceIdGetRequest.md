# V1NatEntriesDeviceIdGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nat_filter** | [**IpfixNatEntryFilter**](IpfixNatEntryFilter.md) |  | [optional] 
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_nat_entries_device_id_get_request import V1NatEntriesDeviceIdGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1NatEntriesDeviceIdGetRequest from a JSON string
v1_nat_entries_device_id_get_request_instance = V1NatEntriesDeviceIdGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1NatEntriesDeviceIdGetRequest.to_json())

# convert the object into a dict
v1_nat_entries_device_id_get_request_dict = v1_nat_entries_device_id_get_request_instance.to_dict()
# create an instance of V1NatEntriesDeviceIdGetRequest from a dict
v1_nat_entries_device_id_get_request_from_dict = V1NatEntriesDeviceIdGetRequest.from_dict(v1_nat_entries_device_id_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



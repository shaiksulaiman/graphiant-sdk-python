# V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**host_name** | **str** |  | [optional] 
**num_interfaces** | **int** |  | [optional] 
**site** | **int** |  | [optional] 
**status** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_lan_segments_vrf_id_devices_get_response_entry import V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry from a JSON string
v1_global_lan_segments_vrf_id_devices_get_response_entry_instance = V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry.from_json(json)
# print the JSON string representation of the object
print(V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry.to_json())

# convert the object into a dict
v1_global_lan_segments_vrf_id_devices_get_response_entry_dict = v1_global_lan_segments_vrf_id_devices_get_response_entry_instance.to_dict()
# create an instance of V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry from a dict
v1_global_lan_segments_vrf_id_devices_get_response_entry_from_dict = V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry.from_dict(v1_global_lan_segments_vrf_id_devices_get_response_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



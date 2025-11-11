# V1GlobalLanSegmentsVrfIdDevicesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**entries** | [**List[V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry]**](V1GlobalLanSegmentsVrfIdDevicesGetResponseEntry.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_lan_segments_vrf_id_devices_get_response import V1GlobalLanSegmentsVrfIdDevicesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalLanSegmentsVrfIdDevicesGetResponse from a JSON string
v1_global_lan_segments_vrf_id_devices_get_response_instance = V1GlobalLanSegmentsVrfIdDevicesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalLanSegmentsVrfIdDevicesGetResponse.to_json())

# convert the object into a dict
v1_global_lan_segments_vrf_id_devices_get_response_dict = v1_global_lan_segments_vrf_id_devices_get_response_instance.to_dict()
# create an instance of V1GlobalLanSegmentsVrfIdDevicesGetResponse from a dict
v1_global_lan_segments_vrf_id_devices_get_response_from_dict = V1GlobalLanSegmentsVrfIdDevicesGetResponse.from_dict(v1_global_lan_segments_vrf_id_devices_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



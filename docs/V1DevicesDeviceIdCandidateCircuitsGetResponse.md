# V1DevicesDeviceIdCandidateCircuitsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuits** | [**List[V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo]**](V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_candidate_circuits_get_response import V1DevicesDeviceIdCandidateCircuitsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdCandidateCircuitsGetResponse from a JSON string
v1_devices_device_id_candidate_circuits_get_response_instance = V1DevicesDeviceIdCandidateCircuitsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdCandidateCircuitsGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_candidate_circuits_get_response_dict = v1_devices_device_id_candidate_circuits_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdCandidateCircuitsGetResponse from a dict
v1_devices_device_id_candidate_circuits_get_response_from_dict = V1DevicesDeviceIdCandidateCircuitsGetResponse.from_dict(v1_devices_device_id_candidate_circuits_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



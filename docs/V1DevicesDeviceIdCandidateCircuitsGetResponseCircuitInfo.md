# V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit** | **str** |  | [optional] 
**interface** | **str** |  | [optional] 
**loopback_interface** | **str** |  | [optional] 
**vrf** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_candidate_circuits_get_response_circuit_info import V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo from a JSON string
v1_devices_device_id_candidate_circuits_get_response_circuit_info_instance = V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo.to_json())

# convert the object into a dict
v1_devices_device_id_candidate_circuits_get_response_circuit_info_dict = v1_devices_device_id_candidate_circuits_get_response_circuit_info_instance.to_dict()
# create an instance of V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo from a dict
v1_devices_device_id_candidate_circuits_get_response_circuit_info_from_dict = V1DevicesDeviceIdCandidateCircuitsGetResponseCircuitInfo.from_dict(v1_devices_device_id_candidate_circuits_get_response_circuit_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



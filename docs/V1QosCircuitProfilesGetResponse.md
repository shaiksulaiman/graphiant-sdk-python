# V1QosCircuitProfilesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**profiles** | [**List[ManaV2QoSProfile]**](ManaV2QoSProfile.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_qos_circuit_profiles_get_response import V1QosCircuitProfilesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1QosCircuitProfilesGetResponse from a JSON string
v1_qos_circuit_profiles_get_response_instance = V1QosCircuitProfilesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1QosCircuitProfilesGetResponse.to_json())

# convert the object into a dict
v1_qos_circuit_profiles_get_response_dict = v1_qos_circuit_profiles_get_response_instance.to_dict()
# create an instance of V1QosCircuitProfilesGetResponse from a dict
v1_qos_circuit_profiles_get_response_from_dict = V1QosCircuitProfilesGetResponse.from_dict(v1_qos_circuit_profiles_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



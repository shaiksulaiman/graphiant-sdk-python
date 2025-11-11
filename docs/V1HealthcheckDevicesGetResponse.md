# V1HealthcheckDevicesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**details** | [**List[HealthcheckStatusDetails]**](HealthcheckStatusDetails.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_healthcheck_devices_get_response import V1HealthcheckDevicesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1HealthcheckDevicesGetResponse from a JSON string
v1_healthcheck_devices_get_response_instance = V1HealthcheckDevicesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1HealthcheckDevicesGetResponse.to_json())

# convert the object into a dict
v1_healthcheck_devices_get_response_dict = v1_healthcheck_devices_get_response_instance.to_dict()
# create an instance of V1HealthcheckDevicesGetResponse from a dict
v1_healthcheck_devices_get_response_from_dict = V1HealthcheckDevicesGetResponse.from_dict(v1_healthcheck_devices_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



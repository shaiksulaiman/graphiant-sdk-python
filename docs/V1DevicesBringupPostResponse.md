# V1DevicesBringupPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**summaries** | [**List[OnboardingOnboardingSummary]**](OnboardingOnboardingSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_bringup_post_response import V1DevicesBringupPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesBringupPostResponse from a JSON string
v1_devices_bringup_post_response_instance = V1DevicesBringupPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesBringupPostResponse.to_json())

# convert the object into a dict
v1_devices_bringup_post_response_dict = v1_devices_bringup_post_response_instance.to_dict()
# create an instance of V1DevicesBringupPostResponse from a dict
v1_devices_bringup_post_response_from_dict = V1DevicesBringupPostResponse.from_dict(v1_devices_bringup_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1OnboardingCloudinitGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloudinit_tokens** | [**List[OnboardingCloudInitToken]**](OnboardingCloudInitToken.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_onboarding_cloudinit_get_response import V1OnboardingCloudinitGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1OnboardingCloudinitGetResponse from a JSON string
v1_onboarding_cloudinit_get_response_instance = V1OnboardingCloudinitGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1OnboardingCloudinitGetResponse.to_json())

# convert the object into a dict
v1_onboarding_cloudinit_get_response_dict = v1_onboarding_cloudinit_get_response_instance.to_dict()
# create an instance of V1OnboardingCloudinitGetResponse from a dict
v1_onboarding_cloudinit_get_response_from_dict = V1OnboardingCloudinitGetResponse.from_dict(v1_onboarding_cloudinit_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



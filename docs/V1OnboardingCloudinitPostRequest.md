# V1OnboardingCloudinitPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloudinit_tokens** | [**List[OnboardingCloudInitToken]**](OnboardingCloudInitToken.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_onboarding_cloudinit_post_request import V1OnboardingCloudinitPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1OnboardingCloudinitPostRequest from a JSON string
v1_onboarding_cloudinit_post_request_instance = V1OnboardingCloudinitPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1OnboardingCloudinitPostRequest.to_json())

# convert the object into a dict
v1_onboarding_cloudinit_post_request_dict = v1_onboarding_cloudinit_post_request_instance.to_dict()
# create an instance of V1OnboardingCloudinitPostRequest from a dict
v1_onboarding_cloudinit_post_request_from_dict = V1OnboardingCloudinitPostRequest.from_dict(v1_onboarding_cloudinit_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



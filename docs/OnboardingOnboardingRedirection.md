# OnboardingOnboardingRedirection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**private_onboarding_gw_addr** | **str** |  | [optional] 
**private_portal_url** | **str** |  | [optional] 
**public_key** | **str** |  | [optional] 
**root_ca** | **str** |  | [optional] 
**signature** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_onboarding_redirection import OnboardingOnboardingRedirection

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingOnboardingRedirection from a JSON string
onboarding_onboarding_redirection_instance = OnboardingOnboardingRedirection.from_json(json)
# print the JSON string representation of the object
print(OnboardingOnboardingRedirection.to_json())

# convert the object into a dict
onboarding_onboarding_redirection_dict = onboarding_onboarding_redirection_instance.to_dict()
# create an instance of OnboardingOnboardingRedirection from a dict
onboarding_onboarding_redirection_from_dict = OnboardingOnboardingRedirection.from_dict(onboarding_onboarding_redirection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



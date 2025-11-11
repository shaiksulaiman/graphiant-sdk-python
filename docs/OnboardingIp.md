# OnboardingIp


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gateway_addr** | **str** |  | [optional] 
**ip_addr** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_ip import OnboardingIp

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingIp from a JSON string
onboarding_ip_instance = OnboardingIp.from_json(json)
# print the JSON string representation of the object
print(OnboardingIp.to_json())

# convert the object into a dict
onboarding_ip_dict = onboarding_ip_instance.to_dict()
# create an instance of OnboardingIp from a dict
onboarding_ip_from_dict = OnboardingIp.from_dict(onboarding_ip_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# OnboardingInterface


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ipv4** | [**OnboardingIp**](OnboardingIp.md) |  | [optional] 
**ipv6** | [**OnboardingIp**](OnboardingIp.md) |  | [optional] 
**name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_interface import OnboardingInterface

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingInterface from a JSON string
onboarding_interface_instance = OnboardingInterface.from_json(json)
# print the JSON string representation of the object
print(OnboardingInterface.to_json())

# convert the object into a dict
onboarding_interface_dict = onboarding_interface_instance.to_dict()
# create an instance of OnboardingInterface from a dict
onboarding_interface_from_dict = OnboardingInterface.from_dict(onboarding_interface_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



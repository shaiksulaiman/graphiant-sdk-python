# OnboardingOnboardingSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**discovered_location** | **str** |  | [optional] 
**first_appeared_on** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ip_detected** | **str** |  | [optional] 
**is_new** | **bool** |  | [optional] 
**state** | **str** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_onboarding_summary import OnboardingOnboardingSummary

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingOnboardingSummary from a JSON string
onboarding_onboarding_summary_instance = OnboardingOnboardingSummary.from_json(json)
# print the JSON string representation of the object
print(OnboardingOnboardingSummary.to_json())

# convert the object into a dict
onboarding_onboarding_summary_dict = onboarding_onboarding_summary_instance.to_dict()
# create an instance of OnboardingOnboardingSummary from a dict
onboarding_onboarding_summary_from_dict = OnboardingOnboardingSummary.from_dict(onboarding_onboarding_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



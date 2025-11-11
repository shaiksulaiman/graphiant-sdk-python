# HealthcheckOnboardingStatusDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**state** | **str** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.healthcheck_onboarding_status_details import HealthcheckOnboardingStatusDetails

# TODO update the JSON string below
json = "{}"
# create an instance of HealthcheckOnboardingStatusDetails from a JSON string
healthcheck_onboarding_status_details_instance = HealthcheckOnboardingStatusDetails.from_json(json)
# print the JSON string representation of the object
print(HealthcheckOnboardingStatusDetails.to_json())

# convert the object into a dict
healthcheck_onboarding_status_details_dict = healthcheck_onboarding_status_details_instance.to_dict()
# create an instance of HealthcheckOnboardingStatusDetails from a dict
healthcheck_onboarding_status_details_from_dict = HealthcheckOnboardingStatusDetails.from_dict(healthcheck_onboarding_status_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



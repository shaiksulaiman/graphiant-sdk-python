# OnboardingPrivateGcsDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**api_key** | **str** |  | [optional] 
**is_disable** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**onboarding_gw_addr** | **str** |  | [optional] 
**portal_url** | **str** |  | [optional] 
**public_portal_url** | **str** |  | [optional] 
**root_ca** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_private_gcs_details import OnboardingPrivateGcsDetails

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingPrivateGcsDetails from a JSON string
onboarding_private_gcs_details_instance = OnboardingPrivateGcsDetails.from_json(json)
# print the JSON string representation of the object
print(OnboardingPrivateGcsDetails.to_json())

# convert the object into a dict
onboarding_private_gcs_details_dict = onboarding_private_gcs_details_instance.to_dict()
# create an instance of OnboardingPrivateGcsDetails from a dict
onboarding_private_gcs_details_from_dict = OnboardingPrivateGcsDetails.from_dict(onboarding_private_gcs_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



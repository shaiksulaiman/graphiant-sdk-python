# OnboardingPrivateGcsInventoryDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_model** | **str** |  | [optional] 
**device_serial** | **str** |  | [optional] 
**private_gcs_id** | **int** |  | [optional] 
**uuid** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_private_gcs_inventory_details import OnboardingPrivateGcsInventoryDetails

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingPrivateGcsInventoryDetails from a JSON string
onboarding_private_gcs_inventory_details_instance = OnboardingPrivateGcsInventoryDetails.from_json(json)
# print the JSON string representation of the object
print(OnboardingPrivateGcsInventoryDetails.to_json())

# convert the object into a dict
onboarding_private_gcs_inventory_details_dict = onboarding_private_gcs_inventory_details_instance.to_dict()
# create an instance of OnboardingPrivateGcsInventoryDetails from a dict
onboarding_private_gcs_inventory_details_from_dict = OnboardingPrivateGcsInventoryDetails.from_dict(onboarding_private_gcs_inventory_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



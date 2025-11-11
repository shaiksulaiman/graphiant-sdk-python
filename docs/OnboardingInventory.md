# OnboardingInventory


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_model** | **str** |  | [optional] 
**device_serial** | **str** |  | [optional] 
**is_delete** | **bool** |  | [optional] 
**uuid** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_inventory import OnboardingInventory

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingInventory from a JSON string
onboarding_inventory_instance = OnboardingInventory.from_json(json)
# print the JSON string representation of the object
print(OnboardingInventory.to_json())

# convert the object into a dict
onboarding_inventory_dict = onboarding_inventory_instance.to_dict()
# create an instance of OnboardingInventory from a dict
onboarding_inventory_from_dict = OnboardingInventory.from_dict(onboarding_inventory_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



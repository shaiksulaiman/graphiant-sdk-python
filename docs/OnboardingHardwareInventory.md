# OnboardingHardwareInventory


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**assigned_on** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**created_on** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**device_model** | **str** |  | [optional] 
**device_serial** | **str** |  | [optional] 
**ek_cert** | **str** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**enterprise_name** | **str** |  | [optional] 
**gek_pub** | **str** |  | [optional] 
**is_core** | **bool** |  | [optional] 
**is_new** | **bool** |  | [optional] 
**is_requested** | **bool** |  | [optional] 
**parent_enterprise_id** | **int** |  | [optional] 
**parent_enterprise_name** | **str** |  | [optional] 
**role** | **str** |  | [optional] 
**use_oauth** | **bool** |  | [optional] 
**uuid** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_hardware_inventory import OnboardingHardwareInventory

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingHardwareInventory from a JSON string
onboarding_hardware_inventory_instance = OnboardingHardwareInventory.from_json(json)
# print the JSON string representation of the object
print(OnboardingHardwareInventory.to_json())

# convert the object into a dict
onboarding_hardware_inventory_dict = onboarding_hardware_inventory_instance.to_dict()
# create an instance of OnboardingHardwareInventory from a dict
onboarding_hardware_inventory_from_dict = OnboardingHardwareInventory.from_dict(onboarding_hardware_inventory_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



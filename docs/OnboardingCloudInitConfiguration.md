# OnboardingCloudInitConfiguration


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_type** | **str** |  | [optional] 
**dns_servers** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 
**interfaces** | [**List[OnboardingInterface]**](OnboardingInterface.md) |  | [optional] 
**local_web_password** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_cloud_init_configuration import OnboardingCloudInitConfiguration

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingCloudInitConfiguration from a JSON string
onboarding_cloud_init_configuration_instance = OnboardingCloudInitConfiguration.from_json(json)
# print the JSON string representation of the object
print(OnboardingCloudInitConfiguration.to_json())

# convert the object into a dict
onboarding_cloud_init_configuration_dict = onboarding_cloud_init_configuration_instance.to_dict()
# create an instance of OnboardingCloudInitConfiguration from a dict
onboarding_cloud_init_configuration_from_dict = OnboardingCloudInitConfiguration.from_dict(onboarding_cloud_init_configuration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



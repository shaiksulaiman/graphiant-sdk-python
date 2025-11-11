# OnboardingCloudInitToken


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloudinit_config** | [**OnboardingCloudInitConfiguration**](OnboardingCloudInitConfiguration.md) |  | [optional] 
**device_id** | **int** |  | [optional] 
**device_serial** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**role** | **str** |  | [optional] 
**token** | [**OnboardingCloudInitTokenToken**](OnboardingCloudInitTokenToken.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_cloud_init_token import OnboardingCloudInitToken

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingCloudInitToken from a JSON string
onboarding_cloud_init_token_instance = OnboardingCloudInitToken.from_json(json)
# print the JSON string representation of the object
print(OnboardingCloudInitToken.to_json())

# convert the object into a dict
onboarding_cloud_init_token_dict = onboarding_cloud_init_token_instance.to_dict()
# create an instance of OnboardingCloudInitToken from a dict
onboarding_cloud_init_token_from_dict = OnboardingCloudInitToken.from_dict(onboarding_cloud_init_token_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



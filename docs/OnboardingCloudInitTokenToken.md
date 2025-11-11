# OnboardingCloudInitTokenToken


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_by_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**expiry_by_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**token** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.onboarding_cloud_init_token_token import OnboardingCloudInitTokenToken

# TODO update the JSON string below
json = "{}"
# create an instance of OnboardingCloudInitTokenToken from a JSON string
onboarding_cloud_init_token_token_instance = OnboardingCloudInitTokenToken.from_json(json)
# print the JSON string representation of the object
print(OnboardingCloudInitTokenToken.to_json())

# convert the object into a dict
onboarding_cloud_init_token_token_dict = onboarding_cloud_init_token_token_instance.to_dict()
# create an instance of OnboardingCloudInitTokenToken from a dict
onboarding_cloud_init_token_token_from_dict = OnboardingCloudInitTokenToken.from_dict(onboarding_cloud_init_token_token_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1PolicyApplicationsGetResponseApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_id** | **int** |  | [optional] 
**description** | **str** |  | [optional] 
**kind** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_applications_get_response_application import V1PolicyApplicationsGetResponseApplication

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyApplicationsGetResponseApplication from a JSON string
v1_policy_applications_get_response_application_instance = V1PolicyApplicationsGetResponseApplication.from_json(json)
# print the JSON string representation of the object
print(V1PolicyApplicationsGetResponseApplication.to_json())

# convert the object into a dict
v1_policy_applications_get_response_application_dict = v1_policy_applications_get_response_application_instance.to_dict()
# create an instance of V1PolicyApplicationsGetResponseApplication from a dict
v1_policy_applications_get_response_application_from_dict = V1PolicyApplicationsGetResponseApplication.from_dict(v1_policy_applications_get_response_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



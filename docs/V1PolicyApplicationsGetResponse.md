# V1PolicyApplicationsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**applications** | [**List[V1PolicyApplicationsGetResponseApplication]**](V1PolicyApplicationsGetResponseApplication.md) |  | [optional] 
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_applications_get_response import V1PolicyApplicationsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyApplicationsGetResponse from a JSON string
v1_policy_applications_get_response_instance = V1PolicyApplicationsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1PolicyApplicationsGetResponse.to_json())

# convert the object into a dict
v1_policy_applications_get_response_dict = v1_policy_applications_get_response_instance.to_dict()
# create an instance of V1PolicyApplicationsGetResponse from a dict
v1_policy_applications_get_response_from_dict = V1PolicyApplicationsGetResponse.from_dict(v1_policy_applications_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



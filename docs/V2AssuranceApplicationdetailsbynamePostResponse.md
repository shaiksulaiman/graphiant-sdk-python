# V2AssuranceApplicationdetailsbynamePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_id_record** | [**AssuranceAppIdRecord**](AssuranceAppIdRecord.md) |  | [optional] 
**app_name_record** | [**AssuranceAppNameRecord**](AssuranceAppNameRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_applicationdetailsbyname_post_response import V2AssuranceApplicationdetailsbynamePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceApplicationdetailsbynamePostResponse from a JSON string
v2_assurance_applicationdetailsbyname_post_response_instance = V2AssuranceApplicationdetailsbynamePostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceApplicationdetailsbynamePostResponse.to_json())

# convert the object into a dict
v2_assurance_applicationdetailsbyname_post_response_dict = v2_assurance_applicationdetailsbyname_post_response_instance.to_dict()
# create an instance of V2AssuranceApplicationdetailsbynamePostResponse from a dict
v2_assurance_applicationdetailsbyname_post_response_from_dict = V2AssuranceApplicationdetailsbynamePostResponse.from_dict(v2_assurance_applicationdetailsbyname_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



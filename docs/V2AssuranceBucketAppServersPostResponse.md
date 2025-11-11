# V2AssuranceBucketAppServersPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_servers** | [**List[AssuranceBucketAppServer]**](AssuranceBucketAppServer.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_bucket_app_servers_post_response import V2AssuranceBucketAppServersPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceBucketAppServersPostResponse from a JSON string
v2_assurance_bucket_app_servers_post_response_instance = V2AssuranceBucketAppServersPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceBucketAppServersPostResponse.to_json())

# convert the object into a dict
v2_assurance_bucket_app_servers_post_response_dict = v2_assurance_bucket_app_servers_post_response_instance.to_dict()
# create an instance of V2AssuranceBucketAppServersPostResponse from a dict
v2_assurance_bucket_app_servers_post_response_from_dict = V2AssuranceBucketAppServersPostResponse.from_dict(v2_assurance_bucket_app_servers_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



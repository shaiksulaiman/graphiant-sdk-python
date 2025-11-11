# V2AssuranceBucketAppServersAllGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_servers** | [**List[AssuranceBucketAppServerList]**](AssuranceBucketAppServerList.md) |  | [optional] 
**time_window** | [**AssuranceTimeWindow**](AssuranceTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_bucket_app_servers_all_get_request import V2AssuranceBucketAppServersAllGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceBucketAppServersAllGetRequest from a JSON string
v2_assurance_bucket_app_servers_all_get_request_instance = V2AssuranceBucketAppServersAllGetRequest.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceBucketAppServersAllGetRequest.to_json())

# convert the object into a dict
v2_assurance_bucket_app_servers_all_get_request_dict = v2_assurance_bucket_app_servers_all_get_request_instance.to_dict()
# create an instance of V2AssuranceBucketAppServersAllGetRequest from a dict
v2_assurance_bucket_app_servers_all_get_request_from_dict = V2AssuranceBucketAppServersAllGetRequest.from_dict(v2_assurance_bucket_app_servers_all_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



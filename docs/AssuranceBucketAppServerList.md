# AssuranceBucketAppServerList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app** | [**AssuranceBucketAppIdentifier**](AssuranceBucketAppIdentifier.md) |  | [optional] 
**servers** | [**List[AssuranceServer]**](AssuranceServer.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_app_server_list import AssuranceBucketAppServerList

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketAppServerList from a JSON string
assurance_bucket_app_server_list_instance = AssuranceBucketAppServerList.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketAppServerList.to_json())

# convert the object into a dict
assurance_bucket_app_server_list_dict = assurance_bucket_app_server_list_instance.to_dict()
# create an instance of AssuranceBucketAppServerList from a dict
assurance_bucket_app_server_list_from_dict = AssuranceBucketAppServerList.from_dict(assurance_bucket_app_server_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



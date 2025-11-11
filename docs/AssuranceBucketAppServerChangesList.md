# AssuranceBucketAppServerChangesList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**added_servers** | [**List[AssuranceServer]**](AssuranceServer.md) |  | [optional] 
**app** | [**AssuranceBucketAppIdentifier**](AssuranceBucketAppIdentifier.md) |  | [optional] 
**removed_servers** | [**List[AssuranceServer]**](AssuranceServer.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_app_server_changes_list import AssuranceBucketAppServerChangesList

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketAppServerChangesList from a JSON string
assurance_bucket_app_server_changes_list_instance = AssuranceBucketAppServerChangesList.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketAppServerChangesList.to_json())

# convert the object into a dict
assurance_bucket_app_server_changes_list_dict = assurance_bucket_app_server_changes_list_instance.to_dict()
# create an instance of AssuranceBucketAppServerChangesList from a dict
assurance_bucket_app_server_changes_list_from_dict = AssuranceBucketAppServerChangesList.from_dict(assurance_bucket_app_server_changes_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AssuranceBucketAppServer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_name** | **str** |  | [optional] 
**app_server_key** | **str** |  | [optional] 
**server_ip** | **str** |  | [optional] 
**server_port** | **str** |  | [optional] 
**server_protocol** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_app_server import AssuranceBucketAppServer

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketAppServer from a JSON string
assurance_bucket_app_server_instance = AssuranceBucketAppServer.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketAppServer.to_json())

# convert the object into a dict
assurance_bucket_app_server_dict = assurance_bucket_app_server_instance.to_dict()
# create an instance of AssuranceBucketAppServer from a dict
assurance_bucket_app_server_from_dict = AssuranceBucketAppServer.from_dict(assurance_bucket_app_server_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



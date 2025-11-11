# ManaV2BucketAppServer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip** | **str** |  | [optional] 
**port** | **int** |  | [optional] 
**protocol** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bucket_app_server import ManaV2BucketAppServer

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BucketAppServer from a JSON string
mana_v2_bucket_app_server_instance = ManaV2BucketAppServer.from_json(json)
# print the JSON string representation of the object
print(ManaV2BucketAppServer.to_json())

# convert the object into a dict
mana_v2_bucket_app_server_dict = mana_v2_bucket_app_server_instance.to_dict()
# create an instance of ManaV2BucketAppServer from a dict
mana_v2_bucket_app_server_from_dict = ManaV2BucketAppServer.from_dict(mana_v2_bucket_app_server_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



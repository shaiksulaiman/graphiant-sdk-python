# ManaV2BucketApp


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_id** | **int** |  | [optional] 
**builtin_app_id** | **int** |  | [optional] 
**custom_app_id** | **int** |  | [optional] 
**is_domain** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**servers** | [**List[ManaV2BucketAppServer]**](ManaV2BucketAppServer.md) |  | [optional] 
**use_all_servers** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bucket_app import ManaV2BucketApp

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BucketApp from a JSON string
mana_v2_bucket_app_instance = ManaV2BucketApp.from_json(json)
# print the JSON string representation of the object
print(ManaV2BucketApp.to_json())

# convert the object into a dict
mana_v2_bucket_app_dict = mana_v2_bucket_app_instance.to_dict()
# create an instance of ManaV2BucketApp from a dict
mana_v2_bucket_app_from_dict = ManaV2BucketApp.from_dict(mana_v2_bucket_app_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



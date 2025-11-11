# AssuranceBucketApp


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_name** | **str** |  | [optional] 
**builtin_app_id** | **int** |  | [optional] 
**custom_app_id** | **int** |  | [optional] 
**exchange_service** | [**AssuranceExchangeServiceIdentifier**](AssuranceExchangeServiceIdentifier.md) |  | [optional] 
**flex_algo** | [**AssuranceFlexAlgoIdentifier**](AssuranceFlexAlgoIdentifier.md) |  | [optional] 
**is_domain** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_bucket_app import AssuranceBucketApp

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceBucketApp from a JSON string
assurance_bucket_app_instance = AssuranceBucketApp.from_json(json)
# print the JSON string representation of the object
print(AssuranceBucketApp.to_json())

# convert the object into a dict
assurance_bucket_app_dict = assurance_bucket_app_instance.to_dict()
# create an instance of AssuranceBucketApp from a dict
assurance_bucket_app_from_dict = AssuranceBucketApp.from_dict(assurance_bucket_app_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1GlobalAppsCategoriesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**entries** | [**List[V1GlobalAppsCategoriesGetResponseEntry]**](V1GlobalAppsCategoriesGetResponseEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_apps_categories_get_response import V1GlobalAppsCategoriesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalAppsCategoriesGetResponse from a JSON string
v1_global_apps_categories_get_response_instance = V1GlobalAppsCategoriesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalAppsCategoriesGetResponse.to_json())

# convert the object into a dict
v1_global_apps_categories_get_response_dict = v1_global_apps_categories_get_response_instance.to_dict()
# create an instance of V1GlobalAppsCategoriesGetResponse from a dict
v1_global_apps_categories_get_response_from_dict = V1GlobalAppsCategoriesGetResponse.from_dict(v1_global_apps_categories_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



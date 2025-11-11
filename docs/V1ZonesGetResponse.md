# V1ZonesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page_info** | [**CommonPageInfo**](CommonPageInfo.md) |  | [optional] 
**zones** | [**List[ManaV2Zone]**](ManaV2Zone.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_zones_get_response import V1ZonesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ZonesGetResponse from a JSON string
v1_zones_get_response_instance = V1ZonesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1ZonesGetResponse.to_json())

# convert the object into a dict
v1_zones_get_response_dict = v1_zones_get_response_instance.to_dict()
# create an instance of V1ZonesGetResponse from a dict
v1_zones_get_response_from_dict = V1ZonesGetResponse.from_dict(v1_zones_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



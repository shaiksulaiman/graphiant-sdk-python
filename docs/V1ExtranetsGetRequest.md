# V1ExtranetsGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**page_request** | [**CommonPageRequest**](CommonPageRequest.md) |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_get_request import V1ExtranetsGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsGetRequest from a JSON string
v1_extranets_get_request_instance = V1ExtranetsGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsGetRequest.to_json())

# convert the object into a dict
v1_extranets_get_request_dict = v1_extranets_get_request_instance.to_dict()
# create an instance of V1ExtranetsGetRequest from a dict
v1_extranets_get_request_from_dict = V1ExtranetsGetRequest.from_dict(v1_extranets_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



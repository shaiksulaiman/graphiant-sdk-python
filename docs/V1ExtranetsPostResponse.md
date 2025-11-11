# V1ExtranetsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy** | [**ManaV2ExtranetPolicy**](ManaV2ExtranetPolicy.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_post_response import V1ExtranetsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsPostResponse from a JSON string
v1_extranets_post_response_instance = V1ExtranetsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsPostResponse.to_json())

# convert the object into a dict
v1_extranets_post_response_dict = v1_extranets_post_response_instance.to_dict()
# create an instance of V1ExtranetsPostResponse from a dict
v1_extranets_post_response_from_dict = V1ExtranetsPostResponse.from_dict(v1_extranets_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



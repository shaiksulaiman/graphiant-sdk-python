# V1ExtranetsIdPutResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy** | [**ManaV2ExtranetPolicy**](ManaV2ExtranetPolicy.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_id_put_response import V1ExtranetsIdPutResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsIdPutResponse from a JSON string
v1_extranets_id_put_response_instance = V1ExtranetsIdPutResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsIdPutResponse.to_json())

# convert the object into a dict
v1_extranets_id_put_response_dict = v1_extranets_id_put_response_instance.to_dict()
# create an instance of V1ExtranetsIdPutResponse from a dict
v1_extranets_id_put_response_from_dict = V1ExtranetsIdPutResponse.from_dict(v1_extranets_id_put_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



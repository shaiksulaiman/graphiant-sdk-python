# V1GroupsIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group** | [**IamGroup**](IamGroup.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_id_get_response import V1GroupsIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsIdGetResponse from a JSON string
v1_groups_id_get_response_instance = V1GroupsIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GroupsIdGetResponse.to_json())

# convert the object into a dict
v1_groups_id_get_response_dict = v1_groups_id_get_response_instance.to_dict()
# create an instance of V1GroupsIdGetResponse from a dict
v1_groups_id_get_response_from_dict = V1GroupsIdGetResponse.from_dict(v1_groups_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



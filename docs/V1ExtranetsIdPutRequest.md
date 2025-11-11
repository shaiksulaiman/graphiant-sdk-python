# V1ExtranetsIdPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy** | [**ManaV2ExtranetPolicyInput**](ManaV2ExtranetPolicyInput.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_id_put_request import V1ExtranetsIdPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsIdPutRequest from a JSON string
v1_extranets_id_put_request_instance = V1ExtranetsIdPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsIdPutRequest.to_json())

# convert the object into a dict
v1_extranets_id_put_request_dict = v1_extranets_id_put_request_instance.to_dict()
# create an instance of V1ExtranetsIdPutRequest from a dict
v1_extranets_id_put_request_from_dict = V1ExtranetsIdPutRequest.from_dict(v1_extranets_id_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



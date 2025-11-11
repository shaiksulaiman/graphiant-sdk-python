# V1ExtranetsIdApplyPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[ManaV2ExtranetDeviceStatus]**](ManaV2ExtranetDeviceStatus.md) |  | [optional] 
**job_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_id_apply_post_response import V1ExtranetsIdApplyPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsIdApplyPostResponse from a JSON string
v1_extranets_id_apply_post_response_instance = V1ExtranetsIdApplyPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsIdApplyPostResponse.to_json())

# convert the object into a dict
v1_extranets_id_apply_post_response_dict = v1_extranets_id_apply_post_response_instance.to_dict()
# create an instance of V1ExtranetsIdApplyPostResponse from a dict
v1_extranets_id_apply_post_response_from_dict = V1ExtranetsIdApplyPostResponse.from_dict(v1_extranets_id_apply_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



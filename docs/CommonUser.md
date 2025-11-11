# CommonUser


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**first_name** | **str** |  | [optional] 
**last_active_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**last_name** | **str** |  | [optional] 
**mfa_factor** | **str** |  | [optional] 
**phone_number** | **str** |  | [optional] 
**time_zone** | **str** |  | [optional] 
**user_id** | **str** |  | [optional] 
**verified** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.common_user import CommonUser

# TODO update the JSON string below
json = "{}"
# create an instance of CommonUser from a JSON string
common_user_instance = CommonUser.from_json(json)
# print the JSON string representation of the object
print(CommonUser.to_json())

# convert the object into a dict
common_user_dict = common_user_instance.to_dict()
# create an instance of CommonUser from a dict
common_user_from_dict = CommonUser.from_dict(common_user_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesBringupTokenPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_token** | **str** |  | [optional] 
**valid_till_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_bringup_token_post_response import V1DevicesBringupTokenPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesBringupTokenPostResponse from a JSON string
v1_devices_bringup_token_post_response_instance = V1DevicesBringupTokenPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesBringupTokenPostResponse.to_json())

# convert the object into a dict
v1_devices_bringup_token_post_response_dict = v1_devices_bringup_token_post_response_instance.to_dict()
# create an instance of V1DevicesBringupTokenPostResponse from a dict
v1_devices_bringup_token_post_response_from_dict = V1DevicesBringupTokenPostResponse.from_dict(v1_devices_bringup_token_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



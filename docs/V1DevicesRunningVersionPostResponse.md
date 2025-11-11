# V1DevicesRunningVersionPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**versions** | [**List[UpgradeRunningSwVersion]**](UpgradeRunningSwVersion.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_running_version_post_response import V1DevicesRunningVersionPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesRunningVersionPostResponse from a JSON string
v1_devices_running_version_post_response_instance = V1DevicesRunningVersionPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesRunningVersionPostResponse.to_json())

# convert the object into a dict
v1_devices_running_version_post_response_dict = v1_devices_running_version_post_response_instance.to_dict()
# create an instance of V1DevicesRunningVersionPostResponse from a dict
v1_devices_running_version_post_response_from_dict = V1DevicesRunningVersionPostResponse.from_dict(v1_devices_running_version_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



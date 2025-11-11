# V1SoftwareRunningDetailsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[V1SoftwareRunningDetailsGetResponseDevice]**](V1SoftwareRunningDetailsGetResponseDevice.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_software_running_details_get_response import V1SoftwareRunningDetailsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SoftwareRunningDetailsGetResponse from a JSON string
v1_software_running_details_get_response_instance = V1SoftwareRunningDetailsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1SoftwareRunningDetailsGetResponse.to_json())

# convert the object into a dict
v1_software_running_details_get_response_dict = v1_software_running_details_get_response_instance.to_dict()
# create an instance of V1SoftwareRunningDetailsGetResponse from a dict
v1_software_running_details_get_response_from_dict = V1SoftwareRunningDetailsGetResponse.from_dict(v1_software_running_details_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



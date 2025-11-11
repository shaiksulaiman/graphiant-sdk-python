# V1LogsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cursor_ref** | **str** |  | [optional] 
**histogram** | [**List[SyslogmonHistogram]**](SyslogmonHistogram.md) |  | [optional] 
**logs** | [**List[SyslogmonLog]**](SyslogmonLog.md) |  | [optional] 
**total_logs** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_logs_post_response import V1LogsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1LogsPostResponse from a JSON string
v1_logs_post_response_instance = V1LogsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1LogsPostResponse.to_json())

# convert the object into a dict
v1_logs_post_response_dict = v1_logs_post_response_instance.to_dict()
# create an instance of V1LogsPostResponse from a dict
v1_logs_post_response_from_dict = V1LogsPostResponse.from_dict(v1_logs_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



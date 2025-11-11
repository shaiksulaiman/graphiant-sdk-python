# V2MonitoringQueuePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[V2MonitoringQueuePostResponseData]**](V2MonitoringQueuePostResponseData.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_queue_post_response import V2MonitoringQueuePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringQueuePostResponse from a JSON string
v2_monitoring_queue_post_response_instance = V2MonitoringQueuePostResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringQueuePostResponse.to_json())

# convert the object into a dict
v2_monitoring_queue_post_response_dict = v2_monitoring_queue_post_response_instance.to_dict()
# create an instance of V2MonitoringQueuePostResponse from a dict
v2_monitoring_queue_post_response_from_dict = V2MonitoringQueuePostResponse.from_dict(v2_monitoring_queue_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



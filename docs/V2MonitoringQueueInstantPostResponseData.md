# V2MonitoringQueueInstantPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**samples** | [**List[StatsmonV2StatsSample]**](StatsmonV2StatsSample.md) |  | [optional] 
**selector** | [**StatsmonV2QueueInstantStatsSelector**](StatsmonV2QueueInstantStatsSelector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_queue_instant_post_response_data import V2MonitoringQueueInstantPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringQueueInstantPostResponseData from a JSON string
v2_monitoring_queue_instant_post_response_data_instance = V2MonitoringQueueInstantPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringQueueInstantPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_queue_instant_post_response_data_dict = v2_monitoring_queue_instant_post_response_data_instance.to_dict()
# create an instance of V2MonitoringQueueInstantPostResponseData from a dict
v2_monitoring_queue_instant_post_response_data_from_dict = V2MonitoringQueueInstantPostResponseData.from_dict(v2_monitoring_queue_instant_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



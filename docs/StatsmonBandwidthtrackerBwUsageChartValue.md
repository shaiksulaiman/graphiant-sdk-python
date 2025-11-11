# StatsmonBandwidthtrackerBwUsageChartValue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**avg_value** | **float** |  | [optional] 
**duration** | **int** |  | [optional] 
**max_value** | **float** |  | [optional] 
**start_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_chart_value import StatsmonBandwidthtrackerBwUsageChartValue

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageChartValue from a JSON string
statsmon_bandwidthtracker_bw_usage_chart_value_instance = StatsmonBandwidthtrackerBwUsageChartValue.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageChartValue.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_chart_value_dict = statsmon_bandwidthtracker_bw_usage_chart_value_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageChartValue from a dict
statsmon_bandwidthtracker_bw_usage_chart_value_from_dict = StatsmonBandwidthtrackerBwUsageChartValue.from_dict(statsmon_bandwidthtracker_bw_usage_chart_value_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



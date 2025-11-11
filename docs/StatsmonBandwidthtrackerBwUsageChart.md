# StatsmonBandwidthtrackerBwUsageChart


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_chart** | [**List[StatsmonBandwidthtrackerBwUsageChartValue]**](StatsmonBandwidthtrackerBwUsageChartValue.md) |  | [optional] 
**percentile_usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_chart import StatsmonBandwidthtrackerBwUsageChart

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageChart from a JSON string
statsmon_bandwidthtracker_bw_usage_chart_instance = StatsmonBandwidthtrackerBwUsageChart.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageChart.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_chart_dict = statsmon_bandwidthtracker_bw_usage_chart_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageChart from a dict
statsmon_bandwidthtracker_bw_usage_chart_from_dict = StatsmonBandwidthtrackerBwUsageChart.from_dict(statsmon_bandwidthtracker_bw_usage_chart_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



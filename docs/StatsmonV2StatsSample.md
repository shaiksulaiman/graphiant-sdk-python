# StatsmonV2StatsSample


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**value** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_stats_sample import StatsmonV2StatsSample

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2StatsSample from a JSON string
statsmon_v2_stats_sample_instance = StatsmonV2StatsSample.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2StatsSample.to_json())

# convert the object into a dict
statsmon_v2_stats_sample_dict = statsmon_v2_stats_sample_instance.to_dict()
# create an instance of StatsmonV2StatsSample from a dict
statsmon_v2_stats_sample_from_dict = StatsmonV2StatsSample.from_dict(statsmon_v2_stats_sample_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



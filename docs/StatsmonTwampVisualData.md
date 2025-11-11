# StatsmonTwampVisualData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_name** | **str** |  | [optional] 
**core_location** | **str** |  | [optional] 
**egress_latency** | **float** |  | [optional] 
**ingress_latency** | **float** |  | [optional] 
**loss_percent** | **float** |  | [optional] 
**probes_rx** | **int** |  | [optional] 
**probes_tx** | **int** |  | [optional] 
**round_trip_latency** | **float** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_twamp_visual_data import StatsmonTwampVisualData

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTwampVisualData from a JSON string
statsmon_twamp_visual_data_instance = StatsmonTwampVisualData.from_json(json)
# print the JSON string representation of the object
print(StatsmonTwampVisualData.to_json())

# convert the object into a dict
statsmon_twamp_visual_data_dict = statsmon_twamp_visual_data_instance.to_dict()
# create an instance of StatsmonTwampVisualData from a dict
statsmon_twamp_visual_data_from_dict = StatsmonTwampVisualData.from_dict(statsmon_twamp_visual_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



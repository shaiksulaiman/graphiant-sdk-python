# StatsmonV2CircuitIncidentsDataSample


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dl_incidents** | [**StatsmonV2CircuitIncidentsDataSampleIncidents**](StatsmonV2CircuitIncidentsDataSampleIncidents.md) |  | [optional] 
**overall_status** | **str** | Overall circuit status based on num of poor/fair incidents. | [optional] 
**total_incidents** | [**StatsmonV2CircuitIncidentsDataSampleIncidents**](StatsmonV2CircuitIncidentsDataSampleIncidents.md) |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ul_incidents** | [**StatsmonV2CircuitIncidentsDataSampleIncidents**](StatsmonV2CircuitIncidentsDataSampleIncidents.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_circuit_incidents_data_sample import StatsmonV2CircuitIncidentsDataSample

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2CircuitIncidentsDataSample from a JSON string
statsmon_v2_circuit_incidents_data_sample_instance = StatsmonV2CircuitIncidentsDataSample.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2CircuitIncidentsDataSample.to_json())

# convert the object into a dict
statsmon_v2_circuit_incidents_data_sample_dict = statsmon_v2_circuit_incidents_data_sample_instance.to_dict()
# create an instance of StatsmonV2CircuitIncidentsDataSample from a dict
statsmon_v2_circuit_incidents_data_sample_from_dict = StatsmonV2CircuitIncidentsDataSample.from_dict(statsmon_v2_circuit_incidents_data_sample_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



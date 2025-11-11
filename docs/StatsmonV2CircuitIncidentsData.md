# StatsmonV2CircuitIncidentsData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**samples** | [**List[StatsmonV2CircuitIncidentsDataSample]**](StatsmonV2CircuitIncidentsDataSample.md) |  | [optional] 
**selector** | [**StatsmonV2CircuitIncidentsSelector**](StatsmonV2CircuitIncidentsSelector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_circuit_incidents_data import StatsmonV2CircuitIncidentsData

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2CircuitIncidentsData from a JSON string
statsmon_v2_circuit_incidents_data_instance = StatsmonV2CircuitIncidentsData.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2CircuitIncidentsData.to_json())

# convert the object into a dict
statsmon_v2_circuit_incidents_data_dict = statsmon_v2_circuit_incidents_data_instance.to_dict()
# create an instance of StatsmonV2CircuitIncidentsData from a dict
statsmon_v2_circuit_incidents_data_from_dict = StatsmonV2CircuitIncidentsData.from_dict(statsmon_v2_circuit_incidents_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



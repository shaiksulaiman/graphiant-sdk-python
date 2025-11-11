# StatsmonCircuitsIncidentsData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dl_incidents** | [**StatsmonCircuitIncidents**](StatsmonCircuitIncidents.md) |  | [optional] 
**overall_status** | **str** | Overall circuit status based on num of poor/fair incidents. | [optional] 
**total_incidents** | [**StatsmonCircuitIncidents**](StatsmonCircuitIncidents.md) |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ul_incidents** | [**StatsmonCircuitIncidents**](StatsmonCircuitIncidents.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_circuits_incidents_data import StatsmonCircuitsIncidentsData

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonCircuitsIncidentsData from a JSON string
statsmon_circuits_incidents_data_instance = StatsmonCircuitsIncidentsData.from_json(json)
# print the JSON string representation of the object
print(StatsmonCircuitsIncidentsData.to_json())

# convert the object into a dict
statsmon_circuits_incidents_data_dict = statsmon_circuits_incidents_data_instance.to_dict()
# create an instance of StatsmonCircuitsIncidentsData from a dict
statsmon_circuits_incidents_data_from_dict = StatsmonCircuitsIncidentsData.from_dict(statsmon_circuits_incidents_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# StatsmonCircuitIncidents


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**num_fair_incidents** | **int** |  | [optional] 
**num_poor_incidents** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_circuit_incidents import StatsmonCircuitIncidents

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonCircuitIncidents from a JSON string
statsmon_circuit_incidents_instance = StatsmonCircuitIncidents.from_json(json)
# print the JSON string representation of the object
print(StatsmonCircuitIncidents.to_json())

# convert the object into a dict
statsmon_circuit_incidents_dict = statsmon_circuit_incidents_instance.to_dict()
# create an instance of StatsmonCircuitIncidents from a dict
statsmon_circuit_incidents_from_dict = StatsmonCircuitIncidents.from_dict(statsmon_circuit_incidents_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



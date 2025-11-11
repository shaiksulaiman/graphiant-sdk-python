# StatsmonCircuitsIncidents


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[StatsmonCircuitsIncidentsData]**](StatsmonCircuitsIncidentsData.md) |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_circuits_incidents import StatsmonCircuitsIncidents

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonCircuitsIncidents from a JSON string
statsmon_circuits_incidents_instance = StatsmonCircuitsIncidents.from_json(json)
# print the JSON string representation of the object
print(StatsmonCircuitsIncidents.to_json())

# convert the object into a dict
statsmon_circuits_incidents_dict = statsmon_circuits_incidents_instance.to_dict()
# create an instance of StatsmonCircuitsIncidents from a dict
statsmon_circuits_incidents_from_dict = StatsmonCircuitsIncidents.from_dict(statsmon_circuits_incidents_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



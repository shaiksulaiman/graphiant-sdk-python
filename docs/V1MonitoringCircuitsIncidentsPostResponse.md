# V1MonitoringCircuitsIncidentsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuits_incidents** | [**List[StatsmonCircuitsIncidents]**](StatsmonCircuitsIncidents.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_monitoring_circuits_incidents_post_response import V1MonitoringCircuitsIncidentsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1MonitoringCircuitsIncidentsPostResponse from a JSON string
v1_monitoring_circuits_incidents_post_response_instance = V1MonitoringCircuitsIncidentsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1MonitoringCircuitsIncidentsPostResponse.to_json())

# convert the object into a dict
v1_monitoring_circuits_incidents_post_response_dict = v1_monitoring_circuits_incidents_post_response_instance.to_dict()
# create an instance of V1MonitoringCircuitsIncidentsPostResponse from a dict
v1_monitoring_circuits_incidents_post_response_from_dict = V1MonitoringCircuitsIncidentsPostResponse.from_dict(v1_monitoring_circuits_incidents_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



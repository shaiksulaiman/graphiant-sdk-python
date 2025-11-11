# V2MonitoringExtranetEdgeStatusGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edge_statuses** | [**List[StatsmonExtranetEdgeStatus]**](StatsmonExtranetEdgeStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_extranet_edge_status_get_response import V2MonitoringExtranetEdgeStatusGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringExtranetEdgeStatusGetResponse from a JSON string
v2_monitoring_extranet_edge_status_get_response_instance = V2MonitoringExtranetEdgeStatusGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringExtranetEdgeStatusGetResponse.to_json())

# convert the object into a dict
v2_monitoring_extranet_edge_status_get_response_dict = v2_monitoring_extranet_edge_status_get_response_instance.to_dict()
# create an instance of V2MonitoringExtranetEdgeStatusGetResponse from a dict
v2_monitoring_extranet_edge_status_get_response_from_dict = V2MonitoringExtranetEdgeStatusGetResponse.from_dict(v2_monitoring_extranet_edge_status_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



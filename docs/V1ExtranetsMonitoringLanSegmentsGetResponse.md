# V1ExtranetsMonitoringLanSegmentsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vrfs** | [**List[V1ExtranetsMonitoringLanSegmentsGetResponseVrf]**](V1ExtranetsMonitoringLanSegmentsGetResponseVrf.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_monitoring_lan_segments_get_response import V1ExtranetsMonitoringLanSegmentsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsMonitoringLanSegmentsGetResponse from a JSON string
v1_extranets_monitoring_lan_segments_get_response_instance = V1ExtranetsMonitoringLanSegmentsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsMonitoringLanSegmentsGetResponse.to_json())

# convert the object into a dict
v1_extranets_monitoring_lan_segments_get_response_dict = v1_extranets_monitoring_lan_segments_get_response_instance.to_dict()
# create an instance of V1ExtranetsMonitoringLanSegmentsGetResponse from a dict
v1_extranets_monitoring_lan_segments_get_response_from_dict = V1ExtranetsMonitoringLanSegmentsGetResponse.from_dict(v1_extranets_monitoring_lan_segments_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



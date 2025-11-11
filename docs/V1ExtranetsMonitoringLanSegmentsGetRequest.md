# V1ExtranetsMonitoringLanSegmentsGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**is_b2_b** | **bool** |  | [optional] 
**is_provider** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_monitoring_lan_segments_get_request import V1ExtranetsMonitoringLanSegmentsGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsMonitoringLanSegmentsGetRequest from a JSON string
v1_extranets_monitoring_lan_segments_get_request_instance = V1ExtranetsMonitoringLanSegmentsGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsMonitoringLanSegmentsGetRequest.to_json())

# convert the object into a dict
v1_extranets_monitoring_lan_segments_get_request_dict = v1_extranets_monitoring_lan_segments_get_request_instance.to_dict()
# create an instance of V1ExtranetsMonitoringLanSegmentsGetRequest from a dict
v1_extranets_monitoring_lan_segments_get_request_from_dict = V1ExtranetsMonitoringLanSegmentsGetRequest.from_dict(v1_extranets_monitoring_lan_segments_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



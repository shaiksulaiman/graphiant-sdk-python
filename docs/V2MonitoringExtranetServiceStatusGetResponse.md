# V2MonitoringExtranetServiceStatusGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**statuses** | [**List[StatsmonExtranetServerStatus]**](StatsmonExtranetServerStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_extranet_service_status_get_response import V2MonitoringExtranetServiceStatusGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringExtranetServiceStatusGetResponse from a JSON string
v2_monitoring_extranet_service_status_get_response_instance = V2MonitoringExtranetServiceStatusGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringExtranetServiceStatusGetResponse.to_json())

# convert the object into a dict
v2_monitoring_extranet_service_status_get_response_dict = v2_monitoring_extranet_service_status_get_response_instance.to_dict()
# create an instance of V2MonitoringExtranetServiceStatusGetResponse from a dict
v2_monitoring_extranet_service_status_get_response_from_dict = V2MonitoringExtranetServiceStatusGetResponse.from_dict(v2_monitoring_extranet_service_status_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



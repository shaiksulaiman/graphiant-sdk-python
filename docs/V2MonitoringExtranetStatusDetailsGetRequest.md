# V2MonitoringExtranetStatusDetailsGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**is_b2_b** | **bool** |  | [optional] 
**is_provider** | **bool** |  | [optional] 
**server_address** | **str** |  | [optional] 
**service_id** | **int** |  | [optional] 
**site_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_extranet_status_details_get_request import V2MonitoringExtranetStatusDetailsGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringExtranetStatusDetailsGetRequest from a JSON string
v2_monitoring_extranet_status_details_get_request_instance = V2MonitoringExtranetStatusDetailsGetRequest.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringExtranetStatusDetailsGetRequest.to_json())

# convert the object into a dict
v2_monitoring_extranet_status_details_get_request_dict = v2_monitoring_extranet_status_details_get_request_instance.to_dict()
# create an instance of V2MonitoringExtranetStatusDetailsGetRequest from a dict
v2_monitoring_extranet_status_details_get_request_from_dict = V2MonitoringExtranetStatusDetailsGetRequest.from_dict(v2_monitoring_extranet_status_details_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V2MonitoringExtranetSiteStatusGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**is_b2_b** | **bool** |  | [optional] 
**is_provider** | **bool** |  | [optional] 
**service_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_extranet_site_status_get_request import V2MonitoringExtranetSiteStatusGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringExtranetSiteStatusGetRequest from a JSON string
v2_monitoring_extranet_site_status_get_request_instance = V2MonitoringExtranetSiteStatusGetRequest.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringExtranetSiteStatusGetRequest.to_json())

# convert the object into a dict
v2_monitoring_extranet_site_status_get_request_dict = v2_monitoring_extranet_site_status_get_request_instance.to_dict()
# create an instance of V2MonitoringExtranetSiteStatusGetRequest from a dict
v2_monitoring_extranet_site_status_get_request_from_dict = V2MonitoringExtranetSiteStatusGetRequest.from_dict(v2_monitoring_extranet_site_status_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



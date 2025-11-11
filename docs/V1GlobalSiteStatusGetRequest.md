# V1GlobalSiteStatusGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ipfix_exported_site_id** | **int** |  | [optional] 
**prefix_set_site_id** | **int** |  | [optional] 
**routing_policy_site_id** | **int** |  | [optional] 
**snmp_site_id** | **int** |  | [optional] 
**syslog_server_site_id** | **int** |  | [optional] 
**traffic_policy_site_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_site_status_get_request import V1GlobalSiteStatusGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSiteStatusGetRequest from a JSON string
v1_global_site_status_get_request_instance = V1GlobalSiteStatusGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSiteStatusGetRequest.to_json())

# convert the object into a dict
v1_global_site_status_get_request_dict = v1_global_site_status_get_request_instance.to_dict()
# create an instance of V1GlobalSiteStatusGetRequest from a dict
v1_global_site_status_get_request_from_dict = V1GlobalSiteStatusGetRequest.from_dict(v1_global_site_status_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



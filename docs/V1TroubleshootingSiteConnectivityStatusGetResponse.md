# V1TroubleshootingSiteConnectivityStatusGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**connectivity_status** | [**List[V1TroubleshootingSiteConnectivityStatusGetResponseSiteStatus]**](V1TroubleshootingSiteConnectivityStatusGetResponseSiteStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_troubleshooting_site_connectivity_status_get_response import V1TroubleshootingSiteConnectivityStatusGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1TroubleshootingSiteConnectivityStatusGetResponse from a JSON string
v1_troubleshooting_site_connectivity_status_get_response_instance = V1TroubleshootingSiteConnectivityStatusGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1TroubleshootingSiteConnectivityStatusGetResponse.to_json())

# convert the object into a dict
v1_troubleshooting_site_connectivity_status_get_response_dict = v1_troubleshooting_site_connectivity_status_get_response_instance.to_dict()
# create an instance of V1TroubleshootingSiteConnectivityStatusGetResponse from a dict
v1_troubleshooting_site_connectivity_status_get_response_from_dict = V1TroubleshootingSiteConnectivityStatusGetResponse.from_dict(v1_troubleshooting_site_connectivity_status_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



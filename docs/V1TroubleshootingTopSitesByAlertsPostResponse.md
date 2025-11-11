# V1TroubleshootingTopSitesByAlertsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_plane** | [**V1TroubleshootingTopSitesByAlertsPostResponseSiteCounts**](V1TroubleshootingTopSitesByAlertsPostResponseSiteCounts.md) |  | [optional] 
**data_plane** | [**V1TroubleshootingTopSitesByAlertsPostResponseSiteCounts**](V1TroubleshootingTopSitesByAlertsPostResponseSiteCounts.md) |  | [optional] 
**system_plane** | [**V1TroubleshootingTopSitesByAlertsPostResponseSiteCounts**](V1TroubleshootingTopSitesByAlertsPostResponseSiteCounts.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_troubleshooting_top_sites_by_alerts_post_response import V1TroubleshootingTopSitesByAlertsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1TroubleshootingTopSitesByAlertsPostResponse from a JSON string
v1_troubleshooting_top_sites_by_alerts_post_response_instance = V1TroubleshootingTopSitesByAlertsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1TroubleshootingTopSitesByAlertsPostResponse.to_json())

# convert the object into a dict
v1_troubleshooting_top_sites_by_alerts_post_response_dict = v1_troubleshooting_top_sites_by_alerts_post_response_instance.to_dict()
# create an instance of V1TroubleshootingTopSitesByAlertsPostResponse from a dict
v1_troubleshooting_top_sites_by_alerts_post_response_from_dict = V1TroubleshootingTopSitesByAlertsPostResponse.from_dict(v1_troubleshooting_top_sites_by_alerts_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1TroubleshootingSiteSiteIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edge_statuses** | [**List[StatsmonTroubleshootingEdgeStatus]**](StatsmonTroubleshootingEdgeStatus.md) |  | [optional] 
**site_name** | **str** |  | [optional] 
**site_status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_troubleshooting_site_site_id_get_response import V1TroubleshootingSiteSiteIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1TroubleshootingSiteSiteIdGetResponse from a JSON string
v1_troubleshooting_site_site_id_get_response_instance = V1TroubleshootingSiteSiteIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1TroubleshootingSiteSiteIdGetResponse.to_json())

# convert the object into a dict
v1_troubleshooting_site_site_id_get_response_dict = v1_troubleshooting_site_site_id_get_response_instance.to_dict()
# create an instance of V1TroubleshootingSiteSiteIdGetResponse from a dict
v1_troubleshooting_site_site_id_get_response_from_dict = V1TroubleshootingSiteSiteIdGetResponse.from_dict(v1_troubleshooting_site_site_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



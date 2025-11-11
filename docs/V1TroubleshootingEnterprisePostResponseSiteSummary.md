# V1TroubleshootingEnterprisePostResponseSiteSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_status** | **str** |  | [optional] 
**data_status** | **str** |  | [optional] 
**overall_status** | **str** |  | [optional] 
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**selected_status** | **str** |  | [optional] 
**site_id** | **int** |  | [optional] 
**site_name** | **str** |  | [optional] 
**system_status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_troubleshooting_enterprise_post_response_site_summary import V1TroubleshootingEnterprisePostResponseSiteSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V1TroubleshootingEnterprisePostResponseSiteSummary from a JSON string
v1_troubleshooting_enterprise_post_response_site_summary_instance = V1TroubleshootingEnterprisePostResponseSiteSummary.from_json(json)
# print the JSON string representation of the object
print(V1TroubleshootingEnterprisePostResponseSiteSummary.to_json())

# convert the object into a dict
v1_troubleshooting_enterprise_post_response_site_summary_dict = v1_troubleshooting_enterprise_post_response_site_summary_instance.to_dict()
# create an instance of V1TroubleshootingEnterprisePostResponseSiteSummary from a dict
v1_troubleshooting_enterprise_post_response_site_summary_from_dict = V1TroubleshootingEnterprisePostResponseSiteSummary.from_dict(v1_troubleshooting_enterprise_post_response_site_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



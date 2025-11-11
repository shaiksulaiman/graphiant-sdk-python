# StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**box** | [**List[StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox]**](StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox.md) |  | [optional] 
**device_id** | **int** |  | [optional] 
**device_region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**peer_device_id** | **int** |  | [optional] 
**peer_device_region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 
**session_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary import StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary from a JSON string
statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_instance = StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary.to_json())

# convert the object into a dict
statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_dict = statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_instance.to_dict()
# create an instance of StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary from a dict
statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_from_dict = StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary.from_dict(statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



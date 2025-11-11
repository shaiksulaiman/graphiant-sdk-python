# StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**device_name** | **str** |  | [optional] 
**region** | [**StatsmonTroubleshootingRegion**](StatsmonTroubleshootingRegion.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_get_qoe_matrix_response_devices_summary import StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary from a JSON string
statsmon_backbonehealth_get_qoe_matrix_response_devices_summary_instance = StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary.to_json())

# convert the object into a dict
statsmon_backbonehealth_get_qoe_matrix_response_devices_summary_dict = statsmon_backbonehealth_get_qoe_matrix_response_devices_summary_instance.to_dict()
# create an instance of StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary from a dict
statsmon_backbonehealth_get_qoe_matrix_response_devices_summary_from_dict = StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary.from_dict(statsmon_backbonehealth_get_qoe_matrix_response_devices_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



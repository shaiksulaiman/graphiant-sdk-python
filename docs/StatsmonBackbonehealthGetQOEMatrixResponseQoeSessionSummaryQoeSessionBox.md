# StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**delay_value** | **float** |  | [optional] 
**end_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**jitter_value** | **float** |  | [optional] 
**loss_value** | **float** |  | [optional] 
**start_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**status** | **str** |  | [optional] 
**value** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_qoe_session_box import StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox from a JSON string
statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_qoe_session_box_instance = StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox.to_json())

# convert the object into a dict
statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_qoe_session_box_dict = statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_qoe_session_box_instance.to_dict()
# create an instance of StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox from a dict
statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_qoe_session_box_from_dict = StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummaryQoeSessionBox.from_dict(statsmon_backbonehealth_get_qoe_matrix_response_qoe_session_summary_qoe_session_box_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



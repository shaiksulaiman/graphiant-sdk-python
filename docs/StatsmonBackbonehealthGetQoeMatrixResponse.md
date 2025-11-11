# StatsmonBackbonehealthGetQoeMatrixResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary]**](StatsmonBackbonehealthGetQOEMatrixResponseDevicesSummary.md) |  | [optional] 
**qoe_matrix** | [**List[StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary]**](StatsmonBackbonehealthGetQOEMatrixResponseQoeSessionSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_backbonehealth_get_qoe_matrix_response import StatsmonBackbonehealthGetQoeMatrixResponse

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBackbonehealthGetQoeMatrixResponse from a JSON string
statsmon_backbonehealth_get_qoe_matrix_response_instance = StatsmonBackbonehealthGetQoeMatrixResponse.from_json(json)
# print the JSON string representation of the object
print(StatsmonBackbonehealthGetQoeMatrixResponse.to_json())

# convert the object into a dict
statsmon_backbonehealth_get_qoe_matrix_response_dict = statsmon_backbonehealth_get_qoe_matrix_response_instance.to_dict()
# create an instance of StatsmonBackbonehealthGetQoeMatrixResponse from a dict
statsmon_backbonehealth_get_qoe_matrix_response_from_dict = StatsmonBackbonehealthGetQoeMatrixResponse.from_dict(statsmon_backbonehealth_get_qoe_matrix_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



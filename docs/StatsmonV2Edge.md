# StatsmonV2Edge


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**a** | **int** |  | [optional] 
**b** | **int** |  | [optional] 
**circuits_info** | [**List[StatsmonV2EdgeedgeCircuitInfo]**](StatsmonV2EdgeedgeCircuitInfo.md) |  | [optional] 
**connections** | [**List[StatsmonV2Connection]**](StatsmonV2Connection.md) |  | [optional] 
**name** | **str** |  | [optional] 
**quality** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_edge import StatsmonV2Edge

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2Edge from a JSON string
statsmon_v2_edge_instance = StatsmonV2Edge.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2Edge.to_json())

# convert the object into a dict
statsmon_v2_edge_dict = statsmon_v2_edge_instance.to_dict()
# create an instance of StatsmonV2Edge from a dict
statsmon_v2_edge_from_dict = StatsmonV2Edge.from_dict(statsmon_v2_edge_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



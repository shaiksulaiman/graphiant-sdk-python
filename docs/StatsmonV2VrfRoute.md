# StatsmonV2VrfRoute


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ipv4_routes** | **int** |  | [optional] 
**ipv6_routes** | **int** |  | [optional] 
**total_routes** | **int** |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_vrf_route import StatsmonV2VrfRoute

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2VrfRoute from a JSON string
statsmon_v2_vrf_route_instance = StatsmonV2VrfRoute.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2VrfRoute.to_json())

# convert the object into a dict
statsmon_v2_vrf_route_dict = statsmon_v2_vrf_route_instance.to_dict()
# create an instance of StatsmonV2VrfRoute from a dict
statsmon_v2_vrf_route_from_dict = StatsmonV2VrfRoute.from_dict(statsmon_v2_vrf_route_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



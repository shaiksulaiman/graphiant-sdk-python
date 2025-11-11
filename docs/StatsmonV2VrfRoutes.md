# StatsmonV2VrfRoutes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**vrf_route** | [**List[StatsmonV2VrfRoute]**](StatsmonV2VrfRoute.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_v2_vrf_routes import StatsmonV2VrfRoutes

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonV2VrfRoutes from a JSON string
statsmon_v2_vrf_routes_instance = StatsmonV2VrfRoutes.from_json(json)
# print the JSON string representation of the object
print(StatsmonV2VrfRoutes.to_json())

# convert the object into a dict
statsmon_v2_vrf_routes_dict = statsmon_v2_vrf_routes_instance.to_dict()
# create an instance of StatsmonV2VrfRoutes from a dict
statsmon_v2_vrf_routes_from_dict = StatsmonV2VrfRoutes.from_dict(statsmon_v2_vrf_routes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



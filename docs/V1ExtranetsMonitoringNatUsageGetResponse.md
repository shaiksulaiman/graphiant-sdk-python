# V1ExtranetsMonitoringNatUsageGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allocated_count** | **int** |  | [optional] 
**allocations** | [**List[V1ExtranetsMonitoringNatUsageGetResponseAllocation]**](V1ExtranetsMonitoringNatUsageGetResponseAllocation.md) |  | [optional] 
**usage_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_monitoring_nat_usage_get_response import V1ExtranetsMonitoringNatUsageGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsMonitoringNatUsageGetResponse from a JSON string
v1_extranets_monitoring_nat_usage_get_response_instance = V1ExtranetsMonitoringNatUsageGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsMonitoringNatUsageGetResponse.to_json())

# convert the object into a dict
v1_extranets_monitoring_nat_usage_get_response_dict = v1_extranets_monitoring_nat_usage_get_response_instance.to_dict()
# create an instance of V1ExtranetsMonitoringNatUsageGetResponse from a dict
v1_extranets_monitoring_nat_usage_get_response_from_dict = V1ExtranetsMonitoringNatUsageGetResponse.from_dict(v1_extranets_monitoring_nat_usage_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1ExtranetsMonitoringNatUsageGetResponseAllocation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**ip_address** | **str** |  | [optional] 
**site_id** | **int** |  | [optional] 
**site_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_monitoring_nat_usage_get_response_allocation import V1ExtranetsMonitoringNatUsageGetResponseAllocation

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsMonitoringNatUsageGetResponseAllocation from a JSON string
v1_extranets_monitoring_nat_usage_get_response_allocation_instance = V1ExtranetsMonitoringNatUsageGetResponseAllocation.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsMonitoringNatUsageGetResponseAllocation.to_json())

# convert the object into a dict
v1_extranets_monitoring_nat_usage_get_response_allocation_dict = v1_extranets_monitoring_nat_usage_get_response_allocation_instance.to_dict()
# create an instance of V1ExtranetsMonitoringNatUsageGetResponseAllocation from a dict
v1_extranets_monitoring_nat_usage_get_response_allocation_from_dict = V1ExtranetsMonitoringNatUsageGetResponseAllocation.from_dict(v1_extranets_monitoring_nat_usage_get_response_allocation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



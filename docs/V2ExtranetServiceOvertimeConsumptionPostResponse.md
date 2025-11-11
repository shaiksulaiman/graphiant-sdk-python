# V2ExtranetServiceOvertimeConsumptionPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dl_agg_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 
**ul_agg_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranet_service_overtime_consumption_post_response import V2ExtranetServiceOvertimeConsumptionPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetServiceOvertimeConsumptionPostResponse from a JSON string
v2_extranet_service_overtime_consumption_post_response_instance = V2ExtranetServiceOvertimeConsumptionPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetServiceOvertimeConsumptionPostResponse.to_json())

# convert the object into a dict
v2_extranet_service_overtime_consumption_post_response_dict = v2_extranet_service_overtime_consumption_post_response_instance.to_dict()
# create an instance of V2ExtranetServiceOvertimeConsumptionPostResponse from a dict
v2_extranet_service_overtime_consumption_post_response_from_dict = V2ExtranetServiceOvertimeConsumptionPostResponse.from_dict(v2_extranet_service_overtime_consumption_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



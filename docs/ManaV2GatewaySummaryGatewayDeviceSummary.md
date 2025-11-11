# ManaV2GatewaySummaryGatewayDeviceSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**interface_id** | **int** |  | [optional] 
**maintenance_mode** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_gateway_summary_gateway_device_summary import ManaV2GatewaySummaryGatewayDeviceSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GatewaySummaryGatewayDeviceSummary from a JSON string
mana_v2_gateway_summary_gateway_device_summary_instance = ManaV2GatewaySummaryGatewayDeviceSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2GatewaySummaryGatewayDeviceSummary.to_json())

# convert the object into a dict
mana_v2_gateway_summary_gateway_device_summary_dict = mana_v2_gateway_summary_gateway_device_summary_instance.to_dict()
# create an instance of ManaV2GatewaySummaryGatewayDeviceSummary from a dict
mana_v2_gateway_summary_gateway_device_summary_from_dict = ManaV2GatewaySummaryGatewayDeviceSummary.from_dict(mana_v2_gateway_summary_gateway_device_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



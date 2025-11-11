# ManaV2GatewaySummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**gateway_device_summary** | [**List[ManaV2GatewaySummaryGatewayDeviceSummary]**](ManaV2GatewaySummaryGatewayDeviceSummary.md) |  | [optional] 
**graphiant_region** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**speed** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**support_status** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_gateway_summary import ManaV2GatewaySummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GatewaySummary from a JSON string
mana_v2_gateway_summary_instance = ManaV2GatewaySummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2GatewaySummary.to_json())

# convert the object into a dict
mana_v2_gateway_summary_dict = mana_v2_gateway_summary_instance.to_dict()
# create an instance of ManaV2GatewaySummary from a dict
mana_v2_gateway_summary_from_dict = ManaV2GatewaySummary.from_dict(mana_v2_gateway_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



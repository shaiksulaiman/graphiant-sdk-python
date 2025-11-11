# ManaV2AzureGatewayDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ms_peering_vlan_id** | **int** |  | [optional] 
**routing_policy** | **str** |  | [optional] 
**service_key** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_azure_gateway_details import ManaV2AzureGatewayDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AzureGatewayDetails from a JSON string
mana_v2_azure_gateway_details_instance = ManaV2AzureGatewayDetails.from_json(json)
# print the JSON string representation of the object
print(ManaV2AzureGatewayDetails.to_json())

# convert the object into a dict
mana_v2_azure_gateway_details_dict = mana_v2_azure_gateway_details_instance.to_dict()
# create an instance of ManaV2AzureGatewayDetails from a dict
mana_v2_azure_gateway_details_from_dict = ManaV2AzureGatewayDetails.from_dict(mana_v2_azure_gateway_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2AwsDirectConnectGateway


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**asn** | **int** |  | [optional] 
**id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**transit_gateways** | [**List[ManaV2AwsTransitGateway]**](ManaV2AwsTransitGateway.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_aws_direct_connect_gateway import ManaV2AwsDirectConnectGateway

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AwsDirectConnectGateway from a JSON string
mana_v2_aws_direct_connect_gateway_instance = ManaV2AwsDirectConnectGateway.from_json(json)
# print the JSON string representation of the object
print(ManaV2AwsDirectConnectGateway.to_json())

# convert the object into a dict
mana_v2_aws_direct_connect_gateway_dict = mana_v2_aws_direct_connect_gateway_instance.to_dict()
# create an instance of ManaV2AwsDirectConnectGateway from a dict
mana_v2_aws_direct_connect_gateway_from_dict = ManaV2AwsDirectConnectGateway.from_dict(mana_v2_aws_direct_connect_gateway_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



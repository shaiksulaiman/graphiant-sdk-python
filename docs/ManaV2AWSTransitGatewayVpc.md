# ManaV2AWSTransitGatewayVpc


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**subnets** | [**List[ManaV2Subnet]**](ManaV2Subnet.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_aws_transit_gateway_vpc import ManaV2AWSTransitGatewayVpc

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AWSTransitGatewayVpc from a JSON string
mana_v2_aws_transit_gateway_vpc_instance = ManaV2AWSTransitGatewayVpc.from_json(json)
# print the JSON string representation of the object
print(ManaV2AWSTransitGatewayVpc.to_json())

# convert the object into a dict
mana_v2_aws_transit_gateway_vpc_dict = mana_v2_aws_transit_gateway_vpc_instance.to_dict()
# create an instance of ManaV2AWSTransitGatewayVpc from a dict
mana_v2_aws_transit_gateway_vpc_from_dict = ManaV2AWSTransitGatewayVpc.from_dict(mana_v2_aws_transit_gateway_vpc_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



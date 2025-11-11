# ManaV2AwsTransitGateway


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**asn** | **int** |  | [optional] 
**id** | **str** |  | [optional] 
**vpcs** | [**List[ManaV2AWSTransitGatewayVpc]**](ManaV2AWSTransitGatewayVpc.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_aws_transit_gateway import ManaV2AwsTransitGateway

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AwsTransitGateway from a JSON string
mana_v2_aws_transit_gateway_instance = ManaV2AwsTransitGateway.from_json(json)
# print the JSON string representation of the object
print(ManaV2AwsTransitGateway.to_json())

# convert the object into a dict
mana_v2_aws_transit_gateway_dict = mana_v2_aws_transit_gateway_instance.to_dict()
# create an instance of ManaV2AwsTransitGateway from a dict
mana_v2_aws_transit_gateway_from_dict = ManaV2AwsTransitGateway.from_dict(mana_v2_aws_transit_gateway_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



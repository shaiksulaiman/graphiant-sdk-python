# ManaV2AWSGatewayDetailsTransitConnection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**credentials** | [**ManaV2AwsCredentials**](ManaV2AwsCredentials.md) |  | [optional] 
**customer_asn** | **int** |  | [optional] 
**gateway** | [**ManaV2AwsDirectConnectGateway**](ManaV2AwsDirectConnectGateway.md) |  | [optional] 
**region** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_aws_gateway_details_transit_connection import ManaV2AWSGatewayDetailsTransitConnection

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AWSGatewayDetailsTransitConnection from a JSON string
mana_v2_aws_gateway_details_transit_connection_instance = ManaV2AWSGatewayDetailsTransitConnection.from_json(json)
# print the JSON string representation of the object
print(ManaV2AWSGatewayDetailsTransitConnection.to_json())

# convert the object into a dict
mana_v2_aws_gateway_details_transit_connection_dict = mana_v2_aws_gateway_details_transit_connection_instance.to_dict()
# create an instance of ManaV2AWSGatewayDetailsTransitConnection from a dict
mana_v2_aws_gateway_details_transit_connection_from_dict = ManaV2AWSGatewayDetailsTransitConnection.from_dict(mana_v2_aws_gateway_details_transit_connection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



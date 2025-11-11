# ManaV2AwsGatewayDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **str** |  | [optional] 
**advance_settings** | [**ManaV2AwsAdvanceSettings**](ManaV2AwsAdvanceSettings.md) |  | [optional] 
**transit_connection** | [**ManaV2AWSGatewayDetailsTransitConnection**](ManaV2AWSGatewayDetailsTransitConnection.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_aws_gateway_details import ManaV2AwsGatewayDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AwsGatewayDetails from a JSON string
mana_v2_aws_gateway_details_instance = ManaV2AwsGatewayDetails.from_json(json)
# print the JSON string representation of the object
print(ManaV2AwsGatewayDetails.to_json())

# convert the object into a dict
mana_v2_aws_gateway_details_dict = mana_v2_aws_gateway_details_instance.to_dict()
# create an instance of ManaV2AwsGatewayDetails from a dict
mana_v2_aws_gateway_details_from_dict = ManaV2AwsGatewayDetails.from_dict(mana_v2_aws_gateway_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



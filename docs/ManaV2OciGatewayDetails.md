# ManaV2OciGatewayDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**fast_connect_ocid** | **str** |  | [optional] 
**routing_policy** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_oci_gateway_details import ManaV2OciGatewayDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OciGatewayDetails from a JSON string
mana_v2_oci_gateway_details_instance = ManaV2OciGatewayDetails.from_json(json)
# print the JSON string representation of the object
print(ManaV2OciGatewayDetails.to_json())

# convert the object into a dict
mana_v2_oci_gateway_details_dict = mana_v2_oci_gateway_details_instance.to_dict()
# create an instance of ManaV2OciGatewayDetails from a dict
mana_v2_oci_gateway_details_from_dict = ManaV2OciGatewayDetails.from_dict(mana_v2_oci_gateway_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



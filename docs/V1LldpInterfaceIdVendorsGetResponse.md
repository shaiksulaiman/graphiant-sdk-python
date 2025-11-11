# V1LldpInterfaceIdVendorsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendors** | [**List[ManaV2VendorDetail]**](ManaV2VendorDetail.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_lldp_interface_id_vendors_get_response import V1LldpInterfaceIdVendorsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1LldpInterfaceIdVendorsGetResponse from a JSON string
v1_lldp_interface_id_vendors_get_response_instance = V1LldpInterfaceIdVendorsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1LldpInterfaceIdVendorsGetResponse.to_json())

# convert the object into a dict
v1_lldp_interface_id_vendors_get_response_dict = v1_lldp_interface_id_vendors_get_response_instance.to_dict()
# create an instance of V1LldpInterfaceIdVendorsGetResponse from a dict
v1_lldp_interface_id_vendors_get_response_from_dict = V1LldpInterfaceIdVendorsGetResponse.from_dict(v1_lldp_interface_id_vendors_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



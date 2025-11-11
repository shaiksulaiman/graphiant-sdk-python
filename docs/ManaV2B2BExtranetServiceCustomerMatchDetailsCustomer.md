# ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**company_name** | **str** |  | [optional] 
**emails** | **List[str]** |  | [optional] 
**id** | **int** |  | [optional] 
**num_sites** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2_b_extranet_service_customer_match_details_customer import ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer from a JSON string
mana_v2_b2_b_extranet_service_customer_match_details_customer_instance = ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer.to_json())

# convert the object into a dict
mana_v2_b2_b_extranet_service_customer_match_details_customer_dict = mana_v2_b2_b_extranet_service_customer_match_details_customer_instance.to_dict()
# create an instance of ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer from a dict
mana_v2_b2_b_extranet_service_customer_match_details_customer_from_dict = ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer.from_dict(mana_v2_b2_b_extranet_service_customer_match_details_customer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



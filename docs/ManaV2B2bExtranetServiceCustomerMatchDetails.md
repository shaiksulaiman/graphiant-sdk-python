# ManaV2B2bExtranetServiceCustomerMatchDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_prefixes** | **List[str]** |  | [optional] 
**customer** | [**ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer**](ManaV2B2BExtranetServiceCustomerMatchDetailsCustomer.md) |  | [optional] 
**service** | [**ManaV2B2BExtranetServiceCustomerMatchDetailsService**](ManaV2B2BExtranetServiceCustomerMatchDetailsService.md) |  | [optional] 
**service_prefixes** | [**List[ManaV2B2BExtranetServiceCustomerMatchDetailsProducerPrefix]**](ManaV2B2BExtranetServiceCustomerMatchDetailsProducerPrefix.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_service_customer_match_details import ManaV2B2bExtranetServiceCustomerMatchDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetServiceCustomerMatchDetails from a JSON string
mana_v2_b2b_extranet_service_customer_match_details_instance = ManaV2B2bExtranetServiceCustomerMatchDetails.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetServiceCustomerMatchDetails.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_service_customer_match_details_dict = mana_v2_b2b_extranet_service_customer_match_details_instance.to_dict()
# create an instance of ManaV2B2bExtranetServiceCustomerMatchDetails from a dict
mana_v2_b2b_extranet_service_customer_match_details_from_dict = ManaV2B2bExtranetServiceCustomerMatchDetails.from_dict(mana_v2_b2b_extranet_service_customer_match_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



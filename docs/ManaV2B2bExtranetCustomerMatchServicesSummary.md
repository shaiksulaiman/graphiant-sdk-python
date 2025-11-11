# ManaV2B2bExtranetCustomerMatchServicesSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**lan_segment** | **int** |  | [optional] 
**matched_customers** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_customer_match_services_summary import ManaV2B2bExtranetCustomerMatchServicesSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetCustomerMatchServicesSummary from a JSON string
mana_v2_b2b_extranet_customer_match_services_summary_instance = ManaV2B2bExtranetCustomerMatchServicesSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetCustomerMatchServicesSummary.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_customer_match_services_summary_dict = mana_v2_b2b_extranet_customer_match_services_summary_instance.to_dict()
# create an instance of ManaV2B2bExtranetCustomerMatchServicesSummary from a dict
mana_v2_b2b_extranet_customer_match_services_summary_from_dict = ManaV2B2bExtranetCustomerMatchServicesSummary.from_dict(mana_v2_b2b_extranet_customer_match_services_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2B2bExtranetCustomerServicesSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_emails** | **List[str]** |  | [optional] 
**id** | **int** |  | [optional] 
**matched_services** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_customer_services_summary import ManaV2B2bExtranetCustomerServicesSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetCustomerServicesSummary from a JSON string
mana_v2_b2b_extranet_customer_services_summary_instance = ManaV2B2bExtranetCustomerServicesSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetCustomerServicesSummary.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_customer_services_summary_dict = mana_v2_b2b_extranet_customer_services_summary_instance.to_dict()
# create an instance of ManaV2B2bExtranetCustomerServicesSummary from a dict
mana_v2_b2b_extranet_customer_services_summary_from_dict = ManaV2B2bExtranetCustomerServicesSummary.from_dict(mana_v2_b2b_extranet_customer_services_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2B2bApplicationCustomerSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_email** | **str** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_application_customer_summary import ManaV2B2bApplicationCustomerSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bApplicationCustomerSummary from a JSON string
mana_v2_b2b_application_customer_summary_instance = ManaV2B2bApplicationCustomerSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bApplicationCustomerSummary.to_json())

# convert the object into a dict
mana_v2_b2b_application_customer_summary_dict = mana_v2_b2b_application_customer_summary_instance.to_dict()
# create an instance of ManaV2B2bApplicationCustomerSummary from a dict
mana_v2_b2b_application_customer_summary_from_dict = ManaV2B2bApplicationCustomerSummary.from_dict(mana_v2_b2b_application_customer_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



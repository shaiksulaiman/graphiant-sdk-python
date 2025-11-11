# ManaV2ContractualBandwidthConsumptionSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expiration_date** | [**ManaV2TimePeriod**](ManaV2TimePeriod.md) |  | [optional] 
**total_consumed_credits** | **float** | All credits consumed over the entirety the enterprise&#39;s contracts | [optional] 
**total_contracted_credits** | **float** | Number of credits agreed upon for the entirety of the current contract | [optional] 
**total_remaining_credits** | **float** | Number of unused credits remaining under the current contract | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_contractual_bandwidth_consumption_summary import ManaV2ContractualBandwidthConsumptionSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ContractualBandwidthConsumptionSummary from a JSON string
mana_v2_contractual_bandwidth_consumption_summary_instance = ManaV2ContractualBandwidthConsumptionSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2ContractualBandwidthConsumptionSummary.to_json())

# convert the object into a dict
mana_v2_contractual_bandwidth_consumption_summary_dict = mana_v2_contractual_bandwidth_consumption_summary_instance.to_dict()
# create an instance of ManaV2ContractualBandwidthConsumptionSummary from a dict
mana_v2_contractual_bandwidth_consumption_summary_from_dict = ManaV2ContractualBandwidthConsumptionSummary.from_dict(mana_v2_contractual_bandwidth_consumption_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



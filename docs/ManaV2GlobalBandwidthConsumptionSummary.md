# ManaV2GlobalBandwidthConsumptionSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allocated_monthly_credits** | **float** | Credits allocated for the current month | [optional] 
**consumed_monthly_credits** | **float** | Credits billed for the current month. It equals the the higher value between the credits allocated and used for the month | [optional] 
**prior_allocated_monthly_credits** | **float** | Credits allocated for the prior month | [optional] 
**prior_consumed_monthly_credits** | **float** | Credits billed for the prior month. | [optional] 
**recommended_monthly_credits** | **float** | Expected amount of credits to allocate for the month to match the overall contracted amount. For monthly-contracted enterprises, this is equivalent to the monthly number of credits being billed while for term-based-contracted enterprises, this is equivalent to the number of credits to use up in this and the following months to use up exactly the number of credits remaining in the contract. | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_global_bandwidth_consumption_summary import ManaV2GlobalBandwidthConsumptionSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GlobalBandwidthConsumptionSummary from a JSON string
mana_v2_global_bandwidth_consumption_summary_instance = ManaV2GlobalBandwidthConsumptionSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2GlobalBandwidthConsumptionSummary.to_json())

# convert the object into a dict
mana_v2_global_bandwidth_consumption_summary_dict = mana_v2_global_bandwidth_consumption_summary_instance.to_dict()
# create an instance of ManaV2GlobalBandwidthConsumptionSummary from a dict
mana_v2_global_bandwidth_consumption_summary_from_dict = ManaV2GlobalBandwidthConsumptionSummary.from_dict(mana_v2_global_bandwidth_consumption_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



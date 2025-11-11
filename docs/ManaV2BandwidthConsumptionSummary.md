# ManaV2BandwidthConsumptionSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**contractual_summary** | [**ManaV2ContractualBandwidthConsumptionSummary**](ManaV2ContractualBandwidthConsumptionSummary.md) |  | [optional] 
**global_summary** | [**ManaV2GlobalBandwidthConsumptionSummary**](ManaV2GlobalBandwidthConsumptionSummary.md) |  | [optional] 
**regional_summaries** | [**Dict[str, ManaV2RegionalBandwidthConsumptionSummary]**](ManaV2RegionalBandwidthConsumptionSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bandwidth_consumption_summary import ManaV2BandwidthConsumptionSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BandwidthConsumptionSummary from a JSON string
mana_v2_bandwidth_consumption_summary_instance = ManaV2BandwidthConsumptionSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2BandwidthConsumptionSummary.to_json())

# convert the object into a dict
mana_v2_bandwidth_consumption_summary_dict = mana_v2_bandwidth_consumption_summary_instance.to_dict()
# create an instance of ManaV2BandwidthConsumptionSummary from a dict
mana_v2_bandwidth_consumption_summary_from_dict = ManaV2BandwidthConsumptionSummary.from_dict(mana_v2_bandwidth_consumption_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



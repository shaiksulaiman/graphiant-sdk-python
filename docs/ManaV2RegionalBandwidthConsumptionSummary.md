# ManaV2RegionalBandwidthConsumptionSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allocation** | [**ManaV2BandwidthInfo**](ManaV2BandwidthInfo.md) |  | [optional] 
**consumed_credits** | **float** | Credits billed for the region. It equals the higher value between total credits allocated and used plus any additional dia consumption | [optional] 
**core_conversion_factor** | **float** | Conversion rate from gigabytes per second to Graphiant credits used for calculating credits on core networks for this region | [optional] 
**gw_conversion_factor** | **float** | Conversion rate from gigabytes per second to Graphiant credits used for calculating credits on core networks for this region | [optional] 
**internet_consumption** | [**ManaV2InternetAccessBandwidthInfo**](ManaV2InternetAccessBandwidthInfo.md) |  | [optional] 
**usage** | [**ManaV2BandwidthInfo**](ManaV2BandwidthInfo.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_regional_bandwidth_consumption_summary import ManaV2RegionalBandwidthConsumptionSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RegionalBandwidthConsumptionSummary from a JSON string
mana_v2_regional_bandwidth_consumption_summary_instance = ManaV2RegionalBandwidthConsumptionSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2RegionalBandwidthConsumptionSummary.to_json())

# convert the object into a dict
mana_v2_regional_bandwidth_consumption_summary_dict = mana_v2_regional_bandwidth_consumption_summary_instance.to_dict()
# create an instance of ManaV2RegionalBandwidthConsumptionSummary from a dict
mana_v2_regional_bandwidth_consumption_summary_from_dict = ManaV2RegionalBandwidthConsumptionSummary.from_dict(mana_v2_regional_bandwidth_consumption_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



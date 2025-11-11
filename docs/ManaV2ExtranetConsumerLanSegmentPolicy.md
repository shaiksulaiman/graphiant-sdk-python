# ManaV2ExtranetConsumerLanSegmentPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_lan_segment** | **int** |  | [optional] 
**restricted_prefixes** | **List[str]** |  | [optional] 
**rules** | [**List[ManaV2ExtranetConsumerNatRule]**](ManaV2ExtranetConsumerNatRule.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_extranet_consumer_lan_segment_policy import ManaV2ExtranetConsumerLanSegmentPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ExtranetConsumerLanSegmentPolicy from a JSON string
mana_v2_extranet_consumer_lan_segment_policy_instance = ManaV2ExtranetConsumerLanSegmentPolicy.from_json(json)
# print the JSON string representation of the object
print(ManaV2ExtranetConsumerLanSegmentPolicy.to_json())

# convert the object into a dict
mana_v2_extranet_consumer_lan_segment_policy_dict = mana_v2_extranet_consumer_lan_segment_policy_instance.to_dict()
# create an instance of ManaV2ExtranetConsumerLanSegmentPolicy from a dict
mana_v2_extranet_consumer_lan_segment_policy_from_dict = ManaV2ExtranetConsumerLanSegmentPolicy.from_dict(mana_v2_extranet_consumer_lan_segment_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



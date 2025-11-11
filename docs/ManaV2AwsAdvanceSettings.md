# ManaV2AwsAdvanceSettings


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_family** | **str** |  | [optional] 
**allowed_prefixes** | **List[str]** |  | [optional] 
**amazon_bgp_router_ip** | **str** |  | [optional] 
**bgp_auth_key** | **str** |  | [optional] 
**customer_bgp_router_ip** | **str** |  | [optional] 
**is_jumbo** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_aws_advance_settings import ManaV2AwsAdvanceSettings

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2AwsAdvanceSettings from a JSON string
mana_v2_aws_advance_settings_instance = ManaV2AwsAdvanceSettings.from_json(json)
# print the JSON string representation of the object
print(ManaV2AwsAdvanceSettings.to_json())

# convert the object into a dict
mana_v2_aws_advance_settings_dict = mana_v2_aws_advance_settings_instance.to_dict()
# create an instance of ManaV2AwsAdvanceSettings from a dict
mana_v2_aws_advance_settings_from_dict = ManaV2AwsAdvanceSettings.from_dict(mana_v2_aws_advance_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



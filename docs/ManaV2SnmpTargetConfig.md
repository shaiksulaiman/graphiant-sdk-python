# ManaV2SnmpTargetConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**community** | **str** |  | [optional] 
**lan_segment** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**notify_filter_profile** | **str** |  | [optional] 
**notify_type** | **str** |  | [optional] 
**source_ip** | **str** |  | [optional] 
**target_ip** | **str** |  | [optional] 
**target_type** | **str** |  | [optional] 
**usm_security_level** | **str** |  | [optional] 
**usm_user_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_target_config import ManaV2SnmpTargetConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpTargetConfig from a JSON string
mana_v2_snmp_target_config_instance = ManaV2SnmpTargetConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpTargetConfig.to_json())

# convert the object into a dict
mana_v2_snmp_target_config_dict = mana_v2_snmp_target_config_instance.to_dict()
# create an instance of ManaV2SnmpTargetConfig from a dict
mana_v2_snmp_target_config_from_dict = ManaV2SnmpTargetConfig.from_dict(mana_v2_snmp_target_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



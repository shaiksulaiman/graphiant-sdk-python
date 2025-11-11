# ManaV2SecurityZoneConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inside** | **str** |  | [optional] 
**pairs** | [**Dict[str, ManaV2NullableSecurityZonePairConfig]**](ManaV2NullableSecurityZonePairConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_zone_config import ManaV2SecurityZoneConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityZoneConfig from a JSON string
mana_v2_security_zone_config_instance = ManaV2SecurityZoneConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityZoneConfig.to_json())

# convert the object into a dict
mana_v2_security_zone_config_dict = mana_v2_security_zone_config_instance.to_dict()
# create an instance of ManaV2SecurityZoneConfig from a dict
mana_v2_security_zone_config_from_dict = ManaV2SecurityZoneConfig.from_dict(mana_v2_security_zone_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



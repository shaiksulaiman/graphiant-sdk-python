# ManaV2SecurityZone


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inside** | **str** |  | [optional] 
**outside** | **str** |  | [optional] 
**ruleset** | **str** |  | [optional] 
**tcp_protection** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_security_zone import ManaV2SecurityZone

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SecurityZone from a JSON string
mana_v2_security_zone_instance = ManaV2SecurityZone.from_json(json)
# print the JSON string representation of the object
print(ManaV2SecurityZone.to_json())

# convert the object into a dict
mana_v2_security_zone_dict = mana_v2_security_zone_instance.to_dict()
# create an instance of ManaV2SecurityZone from a dict
mana_v2_security_zone_from_dict = ManaV2SecurityZone.from_dict(mana_v2_security_zone_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



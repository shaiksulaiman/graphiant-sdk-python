# ManaV2SnmpCommunity


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**community_string** | **str** |  | [optional] 
**id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_community import ManaV2SnmpCommunity

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpCommunity from a JSON string
mana_v2_snmp_community_instance = ManaV2SnmpCommunity.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpCommunity.to_json())

# convert the object into a dict
mana_v2_snmp_community_dict = mana_v2_snmp_community_instance.to_dict()
# create an instance of ManaV2SnmpCommunity from a dict
mana_v2_snmp_community_from_dict = ManaV2SnmpCommunity.from_dict(mana_v2_snmp_community_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



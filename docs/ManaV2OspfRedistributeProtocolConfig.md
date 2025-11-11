# ManaV2OspfRedistributeProtocolConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**metric** | **int** |  | [optional] 
**metric_type** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ospf_redistribute_protocol_config import ManaV2OspfRedistributeProtocolConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2OspfRedistributeProtocolConfig from a JSON string
mana_v2_ospf_redistribute_protocol_config_instance = ManaV2OspfRedistributeProtocolConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2OspfRedistributeProtocolConfig.to_json())

# convert the object into a dict
mana_v2_ospf_redistribute_protocol_config_dict = mana_v2_ospf_redistribute_protocol_config_instance.to_dict()
# create an instance of ManaV2OspfRedistributeProtocolConfig from a dict
mana_v2_ospf_redistribute_protocol_config_from_dict = ManaV2OspfRedistributeProtocolConfig.from_dict(mana_v2_ospf_redistribute_protocol_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



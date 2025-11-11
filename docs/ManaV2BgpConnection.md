# ManaV2BgpConnection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**local_address** | **str** |  | [optional] 
**oper_status** | **bool** |  | [optional] 
**remote_address** | **str** |  | [optional] 
**state** | **str** |  | [optional] 
**time_since_last_oper_change** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**up** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_bgp_connection import ManaV2BgpConnection

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2BgpConnection from a JSON string
mana_v2_bgp_connection_instance = ManaV2BgpConnection.from_json(json)
# print the JSON string representation of the object
print(ManaV2BgpConnection.to_json())

# convert the object into a dict
mana_v2_bgp_connection_dict = mana_v2_bgp_connection_instance.to_dict()
# create an instance of ManaV2BgpConnection from a dict
mana_v2_bgp_connection_from_dict = ManaV2BgpConnection.from_dict(mana_v2_bgp_connection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



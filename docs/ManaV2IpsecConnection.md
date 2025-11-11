# ManaV2IpsecConnection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dest_ip** | **str** |  | [optional] 
**dest_port** | **int** |  | [optional] 
**last_established_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**quality** | **str** |  | [optional] 
**source_ip** | **str** |  | [optional] 
**source_port** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ipsec_connection import ManaV2IpsecConnection

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IpsecConnection from a JSON string
mana_v2_ipsec_connection_instance = ManaV2IpsecConnection.from_json(json)
# print the JSON string representation of the object
print(ManaV2IpsecConnection.to_json())

# convert the object into a dict
mana_v2_ipsec_connection_dict = mana_v2_ipsec_connection_instance.to_dict()
# create an instance of ManaV2IpsecConnection from a dict
mana_v2_ipsec_connection_from_dict = ManaV2IpsecConnection.from_dict(mana_v2_ipsec_connection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



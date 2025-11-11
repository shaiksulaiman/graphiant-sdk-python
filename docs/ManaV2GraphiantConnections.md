# ManaV2GraphiantConnections


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**control_connection** | [**List[ManaV2IpsecConnection]**](ManaV2IpsecConnection.md) |  | [optional] 
**core_connection** | [**List[ManaV2IpsecConnection]**](ManaV2IpsecConnection.md) |  | [optional] 
**management_connection** | [**List[ManaV2IpsecConnection]**](ManaV2IpsecConnection.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_graphiant_connections import ManaV2GraphiantConnections

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GraphiantConnections from a JSON string
mana_v2_graphiant_connections_instance = ManaV2GraphiantConnections.from_json(json)
# print the JSON string representation of the object
print(ManaV2GraphiantConnections.to_json())

# convert the object into a dict
mana_v2_graphiant_connections_dict = mana_v2_graphiant_connections_instance.to_dict()
# create an instance of ManaV2GraphiantConnections from a dict
mana_v2_graphiant_connections_from_dict = ManaV2GraphiantConnections.from_dict(mana_v2_graphiant_connections_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



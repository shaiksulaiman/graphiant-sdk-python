# ManaV2SnmpEngineEndpointConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**addresses** | [**Dict[str, ManaV2NullableSnmpEngineEndpointsAddress]**](ManaV2NullableSnmpEngineEndpointsAddress.md) |  | [optional] 
**auto_ipv4** | **bool** |  | [optional] 
**auto_ipv6** | **bool** |  | [optional] 
**interface** | **str** |  | [optional] 
**lan_segment** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_engine_endpoint_config import ManaV2SnmpEngineEndpointConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpEngineEndpointConfig from a JSON string
mana_v2_snmp_engine_endpoint_config_instance = ManaV2SnmpEngineEndpointConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpEngineEndpointConfig.to_json())

# convert the object into a dict
mana_v2_snmp_engine_endpoint_config_dict = mana_v2_snmp_engine_endpoint_config_instance.to_dict()
# create an instance of ManaV2SnmpEngineEndpointConfig from a dict
mana_v2_snmp_engine_endpoint_config_from_dict = ManaV2SnmpEngineEndpointConfig.from_dict(mana_v2_snmp_engine_endpoint_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



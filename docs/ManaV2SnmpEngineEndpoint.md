# ManaV2SnmpEngineEndpoint


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**addresses** | **List[str]** |  | [optional] 
**auto_ipv4** | **bool** |  | [optional] 
**auto_ipv6** | **bool** |  | [optional] 
**id** | **int** |  | [optional] 
**interface_name** | **str** |  | [optional] 
**lan_segment** | **str** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_snmp_engine_endpoint import ManaV2SnmpEngineEndpoint

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SnmpEngineEndpoint from a JSON string
mana_v2_snmp_engine_endpoint_instance = ManaV2SnmpEngineEndpoint.from_json(json)
# print the JSON string representation of the object
print(ManaV2SnmpEngineEndpoint.to_json())

# convert the object into a dict
mana_v2_snmp_engine_endpoint_dict = mana_v2_snmp_engine_endpoint_instance.to_dict()
# create an instance of ManaV2SnmpEngineEndpoint from a dict
mana_v2_snmp_engine_endpoint_from_dict = ManaV2SnmpEngineEndpoint.from_dict(mana_v2_snmp_engine_endpoint_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



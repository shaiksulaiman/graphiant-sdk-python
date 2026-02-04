# ManaV2PskConfiguration


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cak** | **str** | The Connection Authentication Key (CAK) | [optional] 
**cak_cryptographic_algorithm** | **str** | The cryptographic algorithm for the CAK (required) | [optional] 
**ckn** | **str** | The Connection Key Name (CKN) (required) | [optional] 
**nickname** | **str** | The nickname of the PSK (required) | [optional] 
**start_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_psk_configuration import ManaV2PskConfiguration

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PskConfiguration from a JSON string
mana_v2_psk_configuration_instance = ManaV2PskConfiguration.from_json(json)
# print the JSON string representation of the object
print(ManaV2PskConfiguration.to_json())

# convert the object into a dict
mana_v2_psk_configuration_dict = mana_v2_psk_configuration_instance.to_dict()
# create an instance of ManaV2PskConfiguration from a dict
mana_v2_psk_configuration_from_dict = ManaV2PskConfiguration.from_dict(mana_v2_psk_configuration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



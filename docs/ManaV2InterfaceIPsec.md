# ManaV2InterfaceIPsec


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**anti_replay_window_size** | **int** |  | [optional] 
**dh_group** | **str** |  | [optional] 
**dpd_interval** | **int** |  | [optional] 
**encryption_alg** | **str** |  | [optional] 
**esn** | **bool** |  | [optional] 
**established_time** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ike_integrity** | **str** |  | [optional] 
**ipsec_encryption_alg** | **str** |  | [optional] 
**ipsec_integrity** | **str** |  | [optional] 
**label** | **str** |  | [optional] 
**local_address** | **str** |  | [optional] 
**local_circuit** | **str** |  | [optional] 
**local_ike_peer_identity** | **str** |  | [optional] 
**local_ikesa_spi** | **int** |  | [optional] 
**local_port** | **int** |  | [optional] 
**negotiated_algo** | **str** |  | [optional] 
**oper_state** | **bool** |  | [optional] 
**perfect_forward_secrecy** | **str** |  | [optional] 
**preshared_key** | **str** |  | [optional] 
**protocol** | **str** |  | [optional] 
**reauth_interval** | **int** |  | [optional] 
**rekey_interval** | **int** |  | [optional] 
**remote_address** | **str** |  | [optional] 
**remote_ike_peer_identity** | **str** |  | [optional] 
**remote_ikesa_spi** | **int** |  | [optional] 
**remote_port** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_i_psec import ManaV2InterfaceIPsec

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceIPsec from a JSON string
mana_v2_interface_i_psec_instance = ManaV2InterfaceIPsec.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceIPsec.to_json())

# convert the object into a dict
mana_v2_interface_i_psec_dict = mana_v2_interface_i_psec_instance.to_dict()
# create an instance of ManaV2InterfaceIPsec from a dict
mana_v2_interface_i_psec_from_dict = ManaV2InterfaceIPsec.from_dict(mana_v2_interface_i_psec_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



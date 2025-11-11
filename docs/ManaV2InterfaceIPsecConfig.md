# ManaV2InterfaceIPsecConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**anti_replay_window_size** | **int** |  | [optional] 
**dh_group** | **str** |  | [optional] 
**dpd_interval** | **int** |  | [optional] 
**encryption_alg** | **str** |  | [optional] 
**esn** | **bool** |  | [optional] 
**ike_integrity** | **str** |  | [optional] 
**initiator** | **bool** |  | [optional] 
**ipsec_encryption_alg** | **str** |  | [optional] 
**ipsec_integrity** | **str** |  | [optional] 
**label** | **str** |  | [optional] 
**local_address** | **str** |  | [optional] 
**local_circuit** | **str** |  | [optional] 
**local_ike_peer_identity** | **str** |  | [optional] 
**perfect_forward_secrecy** | **str** |  | [optional] 
**preshared_key** | **str** |  | [optional] 
**reauth_interval** | **int** |  | [optional] 
**rekey_interval** | **int** |  | [optional] 
**remote_address** | **str** |  | [optional] 
**remote_ike_peer_identity** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_interface_i_psec_config import ManaV2InterfaceIPsecConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2InterfaceIPsecConfig from a JSON string
mana_v2_interface_i_psec_config_instance = ManaV2InterfaceIPsecConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2InterfaceIPsecConfig.to_json())

# convert the object into a dict
mana_v2_interface_i_psec_config_dict = mana_v2_interface_i_psec_config_instance.to_dict()
# create an instance of ManaV2InterfaceIPsecConfig from a dict
mana_v2_interface_i_psec_config_from_dict = ManaV2InterfaceIPsecConfig.from_dict(mana_v2_interface_i_psec_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



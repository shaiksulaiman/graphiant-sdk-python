# ManaV2IPsecProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**anti_replay_window_size** | **int** |  | [optional] 
**dpd_interval** | **int** |  | [optional] 
**esn** | **bool** |  | [optional] 
**id** | **int** |  | [optional] 
**ike_dh_group** | **str** |  | [optional] 
**ike_encryption_alg** | **str** |  | [optional] 
**ike_integrity** | **str** |  | [optional] 
**ipsec_encryption_alg** | **str** |  | [optional] 
**ipsec_integrity** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**perfect_forward_secrecy** | **str** |  | [optional] 
**reauth_interval** | **int** |  | [optional] 
**rekey_interval** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_i_psec_profile import ManaV2IPsecProfile

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IPsecProfile from a JSON string
mana_v2_i_psec_profile_instance = ManaV2IPsecProfile.from_json(json)
# print the JSON string representation of the object
print(ManaV2IPsecProfile.to_json())

# convert the object into a dict
mana_v2_i_psec_profile_dict = mana_v2_i_psec_profile_instance.to_dict()
# create an instance of ManaV2IPsecProfile from a dict
mana_v2_i_psec_profile_from_dict = ManaV2IPsecProfile.from_dict(mana_v2_i_psec_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



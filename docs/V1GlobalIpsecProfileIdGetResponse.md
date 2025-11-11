# V1GlobalIpsecProfileIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ipsec_profile** | [**ManaV2IPsecProfile**](ManaV2IPsecProfile.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_ipsec_profile_id_get_response import V1GlobalIpsecProfileIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalIpsecProfileIdGetResponse from a JSON string
v1_global_ipsec_profile_id_get_response_instance = V1GlobalIpsecProfileIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalIpsecProfileIdGetResponse.to_json())

# convert the object into a dict
v1_global_ipsec_profile_id_get_response_dict = v1_global_ipsec_profile_id_get_response_instance.to_dict()
# create an instance of V1GlobalIpsecProfileIdGetResponse from a dict
v1_global_ipsec_profile_id_get_response_from_dict = V1GlobalIpsecProfileIdGetResponse.from_dict(v1_global_ipsec_profile_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



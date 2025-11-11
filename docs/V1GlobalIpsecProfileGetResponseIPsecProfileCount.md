# V1GlobalIpsecProfileGetResponseIPsecProfileCount


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**count** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**ipsec_profile_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_ipsec_profile_get_response_i_psec_profile_count import V1GlobalIpsecProfileGetResponseIPsecProfileCount

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalIpsecProfileGetResponseIPsecProfileCount from a JSON string
v1_global_ipsec_profile_get_response_i_psec_profile_count_instance = V1GlobalIpsecProfileGetResponseIPsecProfileCount.from_json(json)
# print the JSON string representation of the object
print(V1GlobalIpsecProfileGetResponseIPsecProfileCount.to_json())

# convert the object into a dict
v1_global_ipsec_profile_get_response_i_psec_profile_count_dict = v1_global_ipsec_profile_get_response_i_psec_profile_count_instance.to_dict()
# create an instance of V1GlobalIpsecProfileGetResponseIPsecProfileCount from a dict
v1_global_ipsec_profile_get_response_i_psec_profile_count_from_dict = V1GlobalIpsecProfileGetResponseIPsecProfileCount.from_dict(v1_global_ipsec_profile_get_response_i_psec_profile_count_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



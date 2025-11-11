# ManaV2B2bExtranetApplicationInviteResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_email** | **str** |  | [optional] 
**consumer_burst_size** | **int** |  | [optional] 
**consumer_bw_site** | **int** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**maximum_site_count** | **int** |  | [optional] 
**service_prefixes** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_application_invite_response import ManaV2B2bExtranetApplicationInviteResponse

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetApplicationInviteResponse from a JSON string
mana_v2_b2b_extranet_application_invite_response_instance = ManaV2B2bExtranetApplicationInviteResponse.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetApplicationInviteResponse.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_application_invite_response_dict = mana_v2_b2b_extranet_application_invite_response_instance.to_dict()
# create an instance of ManaV2B2bExtranetApplicationInviteResponse from a dict
mana_v2_b2b_extranet_application_invite_response_from_dict = ManaV2B2bExtranetApplicationInviteResponse.from_dict(mana_v2_b2b_extranet_application_invite_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



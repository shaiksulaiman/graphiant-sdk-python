# V2AssuranceCreateDnsproxyEntryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dnsproxy_entry_id** | **str** | dns proxy table entry id (required) | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_create_dnsproxy_entry_post_response import V2AssuranceCreateDnsproxyEntryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceCreateDnsproxyEntryPostResponse from a JSON string
v2_assurance_create_dnsproxy_entry_post_response_instance = V2AssuranceCreateDnsproxyEntryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceCreateDnsproxyEntryPostResponse.to_json())

# convert the object into a dict
v2_assurance_create_dnsproxy_entry_post_response_dict = v2_assurance_create_dnsproxy_entry_post_response_instance.to_dict()
# create an instance of V2AssuranceCreateDnsproxyEntryPostResponse from a dict
v2_assurance_create_dnsproxy_entry_post_response_from_dict = V2AssuranceCreateDnsproxyEntryPostResponse.from_dict(v2_assurance_create_dnsproxy_entry_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



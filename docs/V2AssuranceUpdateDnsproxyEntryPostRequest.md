# V2AssuranceUpdateDnsproxyEntryPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dnsproxy_entry** | [**AssuranceDnsProxyEntry**](AssuranceDnsProxyEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_update_dnsproxy_entry_post_request import V2AssuranceUpdateDnsproxyEntryPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceUpdateDnsproxyEntryPostRequest from a JSON string
v2_assurance_update_dnsproxy_entry_post_request_instance = V2AssuranceUpdateDnsproxyEntryPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceUpdateDnsproxyEntryPostRequest.to_json())

# convert the object into a dict
v2_assurance_update_dnsproxy_entry_post_request_dict = v2_assurance_update_dnsproxy_entry_post_request_instance.to_dict()
# create an instance of V2AssuranceUpdateDnsproxyEntryPostRequest from a dict
v2_assurance_update_dnsproxy_entry_post_request_from_dict = V2AssuranceUpdateDnsproxyEntryPostRequest.from_dict(v2_assurance_update_dnsproxy_entry_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



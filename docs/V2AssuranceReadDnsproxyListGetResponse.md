# V2AssuranceReadDnsproxyListGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dnsproxy_list** | [**List[AssuranceDnsProxyEntry]**](AssuranceDnsProxyEntry.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_read_dnsproxy_list_get_response import V2AssuranceReadDnsproxyListGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceReadDnsproxyListGetResponse from a JSON string
v2_assurance_read_dnsproxy_list_get_response_instance = V2AssuranceReadDnsproxyListGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceReadDnsproxyListGetResponse.to_json())

# convert the object into a dict
v2_assurance_read_dnsproxy_list_get_response_dict = v2_assurance_read_dnsproxy_list_get_response_instance.to_dict()
# create an instance of V2AssuranceReadDnsproxyListGetResponse from a dict
v2_assurance_read_dnsproxy_list_get_response_from_dict = V2AssuranceReadDnsproxyListGetResponse.from_dict(v2_assurance_read_dnsproxy_list_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



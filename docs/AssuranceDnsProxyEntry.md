# AssuranceDnsProxyEntry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dnsproxy_entry_id** | **str** | dns proxy table entry id (required) | 
**ip_list** | **List[str]** |  | 
**name** | **str** | name of the entry  (required) | 
**name_text** | **str** | user defined name of the record (required) | 
**port_list** | **List[str]** |  | 
**protocol** | **str** | protocol to exclude (required) | 

## Example

```python
from graphiant_sdk.models.assurance_dns_proxy_entry import AssuranceDnsProxyEntry

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceDnsProxyEntry from a JSON string
assurance_dns_proxy_entry_instance = AssuranceDnsProxyEntry.from_json(json)
# print the JSON string representation of the object
print(AssuranceDnsProxyEntry.to_json())

# convert the object into a dict
assurance_dns_proxy_entry_dict = assurance_dns_proxy_entry_instance.to_dict()
# create an instance of AssuranceDnsProxyEntry from a dict
assurance_dns_proxy_entry_from_dict = AssuranceDnsProxyEntry.from_dict(assurance_dns_proxy_entry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



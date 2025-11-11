# IpfixClientUsageSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**client_ip_address** | **str** |  | [optional] 
**usage** | **int** | data used in kilo bytes | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_client_usage_summary import IpfixClientUsageSummary

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixClientUsageSummary from a JSON string
ipfix_client_usage_summary_instance = IpfixClientUsageSummary.from_json(json)
# print the JSON string representation of the object
print(IpfixClientUsageSummary.to_json())

# convert the object into a dict
ipfix_client_usage_summary_dict = ipfix_client_usage_summary_instance.to_dict()
# create an instance of IpfixClientUsageSummary from a dict
ipfix_client_usage_summary_from_dict = IpfixClientUsageSummary.from_dict(ipfix_client_usage_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



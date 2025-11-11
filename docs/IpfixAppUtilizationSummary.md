# IpfixAppUtilizationSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_id** | **int** |  | [optional] 
**app_name** | **str** |  | [optional] 
**usage** | **int** | application usage in kilo bytes | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_utilization_summary import IpfixAppUtilizationSummary

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppUtilizationSummary from a JSON string
ipfix_app_utilization_summary_instance = IpfixAppUtilizationSummary.from_json(json)
# print the JSON string representation of the object
print(IpfixAppUtilizationSummary.to_json())

# convert the object into a dict
ipfix_app_utilization_summary_dict = ipfix_app_utilization_summary_instance.to_dict()
# create an instance of IpfixAppUtilizationSummary from a dict
ipfix_app_utilization_summary_from_dict = IpfixAppUtilizationSummary.from_dict(ipfix_app_utilization_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



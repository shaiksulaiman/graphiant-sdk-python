# IpfixAppStateSummaryCount


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_health** | **Dict[str, int]** |  | [optional] 
**app_incidents** | [**IpfixAppIncidents**](IpfixAppIncidents.md) |  | [optional] 
**apps_on_device_count** | **int** |  | [optional] 
**average_qoe** | **float** |  | [optional] 
**circuits_incidents** | [**List[StatsmonCircuitsIncidents]**](StatsmonCircuitsIncidents.md) |  | [optional] 
**circuits_incidentsv2** | [**List[StatsmonV2CircuitIncidents]**](StatsmonV2CircuitIncidents.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_state_summary_count import IpfixAppStateSummaryCount

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppStateSummaryCount from a JSON string
ipfix_app_state_summary_count_instance = IpfixAppStateSummaryCount.from_json(json)
# print the JSON string representation of the object
print(IpfixAppStateSummaryCount.to_json())

# convert the object into a dict
ipfix_app_state_summary_count_dict = ipfix_app_state_summary_count_instance.to_dict()
# create an instance of IpfixAppStateSummaryCount from a dict
ipfix_app_state_summary_count_from_dict = IpfixAppStateSummaryCount.from_dict(ipfix_app_state_summary_count_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



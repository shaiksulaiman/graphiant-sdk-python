# IpfixAppIncidents


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[IpfixAppIncidentsData]**](IpfixAppIncidentsData.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_incidents import IpfixAppIncidents

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppIncidents from a JSON string
ipfix_app_incidents_instance = IpfixAppIncidents.from_json(json)
# print the JSON string representation of the object
print(IpfixAppIncidents.to_json())

# convert the object into a dict
ipfix_app_incidents_dict = ipfix_app_incidents_instance.to_dict()
# create an instance of IpfixAppIncidents from a dict
ipfix_app_incidents_from_dict = IpfixAppIncidents.from_dict(ipfix_app_incidents_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



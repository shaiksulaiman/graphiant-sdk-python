# IpfixAppIncidentsData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_count** | **int** | number of apps running in this time bucket | [optional] 
**app_status** | **str** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_incidents_data import IpfixAppIncidentsData

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppIncidentsData from a JSON string
ipfix_app_incidents_data_instance = IpfixAppIncidentsData.from_json(json)
# print the JSON string representation of the object
print(IpfixAppIncidentsData.to_json())

# convert the object into a dict
ipfix_app_incidents_data_dict = ipfix_app_incidents_data_instance.to_dict()
# create an instance of IpfixAppIncidentsData from a dict
ipfix_app_incidents_data_from_dict = IpfixAppIncidentsData.from_dict(ipfix_app_incidents_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



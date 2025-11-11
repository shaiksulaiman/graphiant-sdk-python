# AssuranceApplicationFlow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_name** | **str** |  | [optional] 
**client_ip** | **str** |  | [optional] 
**client_site** | [**AssuranceSite**](AssuranceSite.md) |  | [optional] 
**first_seen_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**lan_segment** | **str** |  | [optional] 
**last_seen_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**server_ip** | **str** |  | [optional] 
**server_port** | **int** |  | [optional] 
**server_site** | [**AssuranceSite**](AssuranceSite.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_application_flow import AssuranceApplicationFlow

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceApplicationFlow from a JSON string
assurance_application_flow_instance = AssuranceApplicationFlow.from_json(json)
# print the JSON string representation of the object
print(AssuranceApplicationFlow.to_json())

# convert the object into a dict
assurance_application_flow_dict = assurance_application_flow_instance.to_dict()
# create an instance of AssuranceApplicationFlow from a dict
assurance_application_flow_from_dict = AssuranceApplicationFlow.from_dict(assurance_application_flow_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



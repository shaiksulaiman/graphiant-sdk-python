# AssuranceServer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**server_ip** | **str** |  | [optional] 
**server_port** | **str** |  | [optional] 
**server_protocol** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_server import AssuranceServer

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceServer from a JSON string
assurance_server_instance = AssuranceServer.from_json(json)
# print the JSON string representation of the object
print(AssuranceServer.to_json())

# convert the object into a dict
assurance_server_dict = assurance_server_instance.to_dict()
# create an instance of AssuranceServer from a dict
assurance_server_from_dict = AssuranceServer.from_dict(assurance_server_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



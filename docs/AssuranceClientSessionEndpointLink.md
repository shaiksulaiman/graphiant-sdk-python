# AssuranceClientSessionEndpointLink


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuit_name** | **str** |  | [optional] 
**jitter** | **float** |  | [optional] 
**latency** | **float** |  | [optional] 
**loss** | **float** |  | [optional] 
**pop_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_client_session_endpoint_link import AssuranceClientSessionEndpointLink

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceClientSessionEndpointLink from a JSON string
assurance_client_session_endpoint_link_instance = AssuranceClientSessionEndpointLink.from_json(json)
# print the JSON string representation of the object
print(AssuranceClientSessionEndpointLink.to_json())

# convert the object into a dict
assurance_client_session_endpoint_link_dict = assurance_client_session_endpoint_link_instance.to_dict()
# create an instance of AssuranceClientSessionEndpointLink from a dict
assurance_client_session_endpoint_link_from_dict = AssuranceClientSessionEndpointLink.from_dict(assurance_client_session_endpoint_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



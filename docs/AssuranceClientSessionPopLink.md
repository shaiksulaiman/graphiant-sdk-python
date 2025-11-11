# AssuranceClientSessionPopLink


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_pop_name** | **str** |  | [optional] 
**jitter** | **float** |  | [optional] 
**latency** | **float** |  | [optional] 
**loss** | **float** |  | [optional] 
**second_pop_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_client_session_pop_link import AssuranceClientSessionPopLink

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceClientSessionPopLink from a JSON string
assurance_client_session_pop_link_instance = AssuranceClientSessionPopLink.from_json(json)
# print the JSON string representation of the object
print(AssuranceClientSessionPopLink.to_json())

# convert the object into a dict
assurance_client_session_pop_link_dict = assurance_client_session_pop_link_instance.to_dict()
# create an instance of AssuranceClientSessionPopLink from a dict
assurance_client_session_pop_link_from_dict = AssuranceClientSessionPopLink.from_dict(assurance_client_session_pop_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



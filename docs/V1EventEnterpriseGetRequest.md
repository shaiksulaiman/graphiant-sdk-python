# V1EventEnterpriseGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enterprise_id** | **int** | Well known enterprise_id (required) | 
**filter** | [**EventEventFilter**](EventEventFilter.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_event_enterprise_get_request import V1EventEnterpriseGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1EventEnterpriseGetRequest from a JSON string
v1_event_enterprise_get_request_instance = V1EventEnterpriseGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1EventEnterpriseGetRequest.to_json())

# convert the object into a dict
v1_event_enterprise_get_request_dict = v1_event_enterprise_get_request_instance.to_dict()
# create an instance of V1EventEnterpriseGetRequest from a dict
v1_event_enterprise_get_request_from_dict = V1EventEnterpriseGetRequest.from_dict(v1_event_enterprise_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



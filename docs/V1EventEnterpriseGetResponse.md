# V1EventEnterpriseGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**events** | [**List[EventEvent]**](EventEvent.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_event_enterprise_get_response import V1EventEnterpriseGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EventEnterpriseGetResponse from a JSON string
v1_event_enterprise_get_response_instance = V1EventEnterpriseGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1EventEnterpriseGetResponse.to_json())

# convert the object into a dict
v1_event_enterprise_get_response_dict = v1_event_enterprise_get_response_instance.to_dict()
# create an instance of V1EventEnterpriseGetResponse from a dict
v1_event_enterprise_get_response_from_dict = V1EventEnterpriseGetResponse.from_dict(v1_event_enterprise_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



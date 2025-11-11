# V2ExtranetsMonitoringConsumersPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumers** | [**List[ManaV2Consumer]**](ManaV2Consumer.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranets_monitoring_consumers_post_response import V2ExtranetsMonitoringConsumersPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetsMonitoringConsumersPostResponse from a JSON string
v2_extranets_monitoring_consumers_post_response_instance = V2ExtranetsMonitoringConsumersPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetsMonitoringConsumersPostResponse.to_json())

# convert the object into a dict
v2_extranets_monitoring_consumers_post_response_dict = v2_extranets_monitoring_consumers_post_response_instance.to_dict()
# create an instance of V2ExtranetsMonitoringConsumersPostResponse from a dict
v2_extranets_monitoring_consumers_post_response_from_dict = V2ExtranetsMonitoringConsumersPostResponse.from_dict(v2_extranets_monitoring_consumers_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



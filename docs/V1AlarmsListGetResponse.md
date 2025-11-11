# V1AlarmsListGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alarms** | [**List[AlarmsAlarmData]**](AlarmsAlarmData.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_alarms_list_get_response import V1AlarmsListGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AlarmsListGetResponse from a JSON string
v1_alarms_list_get_response_instance = V1AlarmsListGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1AlarmsListGetResponse.to_json())

# convert the object into a dict
v1_alarms_list_get_response_dict = v1_alarms_list_get_response_instance.to_dict()
# create an instance of V1AlarmsListGetResponse from a dict
v1_alarms_list_get_response_from_dict = V1AlarmsListGetResponse.from_dict(v1_alarms_list_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



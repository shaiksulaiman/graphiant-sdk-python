# V1ActivityLogsPostResponseActivityItems


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**items** | [**List[AuditActivityItem]**](AuditActivityItem.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_activity_logs_post_response_activity_items import V1ActivityLogsPostResponseActivityItems

# TODO update the JSON string below
json = "{}"
# create an instance of V1ActivityLogsPostResponseActivityItems from a JSON string
v1_activity_logs_post_response_activity_items_instance = V1ActivityLogsPostResponseActivityItems.from_json(json)
# print the JSON string representation of the object
print(V1ActivityLogsPostResponseActivityItems.to_json())

# convert the object into a dict
v1_activity_logs_post_response_activity_items_dict = v1_activity_logs_post_response_activity_items_instance.to_dict()
# create an instance of V1ActivityLogsPostResponseActivityItems from a dict
v1_activity_logs_post_response_activity_items_from_dict = V1ActivityLogsPostResponseActivityItems.from_dict(v1_activity_logs_post_response_activity_items_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



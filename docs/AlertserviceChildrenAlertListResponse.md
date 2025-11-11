# AlertserviceChildrenAlertListResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alert_list** | [**List[AlertserviceAlertRecord]**](AlertserviceAlertRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.alertservice_children_alert_list_response import AlertserviceChildrenAlertListResponse

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceChildrenAlertListResponse from a JSON string
alertservice_children_alert_list_response_instance = AlertserviceChildrenAlertListResponse.from_json(json)
# print the JSON string representation of the object
print(AlertserviceChildrenAlertListResponse.to_json())

# convert the object into a dict
alertservice_children_alert_list_response_dict = alertservice_children_alert_list_response_instance.to_dict()
# create an instance of AlertserviceChildrenAlertListResponse from a dict
alertservice_children_alert_list_response_from_dict = AlertserviceChildrenAlertListResponse.from_dict(alertservice_children_alert_list_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V2NotificationmutelistRuleIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**records** | [**List[AlertserviceAllowAlertNotifcationListRecord]**](AlertserviceAllowAlertNotifcationListRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_notificationmutelist_rule_id_get_response import V2NotificationmutelistRuleIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2NotificationmutelistRuleIdGetResponse from a JSON string
v2_notificationmutelist_rule_id_get_response_instance = V2NotificationmutelistRuleIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2NotificationmutelistRuleIdGetResponse.to_json())

# convert the object into a dict
v2_notificationmutelist_rule_id_get_response_dict = v2_notificationmutelist_rule_id_get_response_instance.to_dict()
# create an instance of V2NotificationmutelistRuleIdGetResponse from a dict
v2_notificationmutelist_rule_id_get_response_from_dict = V2NotificationmutelistRuleIdGetResponse.from_dict(v2_notificationmutelist_rule_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



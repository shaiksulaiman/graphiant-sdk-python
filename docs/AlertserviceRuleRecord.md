# AlertserviceRuleRecord


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alarm_clear** | **str** | Condition for triggering recovery | [optional] 
**alarm_set** | **str** | Condition for triggering alert (required) | [optional] 
**allow_count** | **int** | Number of entities  allowed/excluded (required) | [optional] 
**category** | **str** | Category of the rule (required) | [optional] 
**enabled** | **bool** | Whether the rule is enabled or disabled (required) | [optional] 
**plane** | **str** | Plane of the rule (required) | [optional] 
**priority** | **str** | Priority of taking action against the rule (required) | [optional] 
**rule_id** | **str** | Unique id of the rule (required) | [optional] 
**rule_name** | **str** | Name of the rule (required) | [optional] 

## Example

```python
from graphiant_sdk.models.alertservice_rule_record import AlertserviceRuleRecord

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceRuleRecord from a JSON string
alertservice_rule_record_instance = AlertserviceRuleRecord.from_json(json)
# print the JSON string representation of the object
print(AlertserviceRuleRecord.to_json())

# convert the object into a dict
alertservice_rule_record_dict = alertservice_rule_record_instance.to_dict()
# create an instance of AlertserviceRuleRecord from a dict
alertservice_rule_record_from_dict = AlertserviceRuleRecord.from_dict(alertservice_rule_record_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



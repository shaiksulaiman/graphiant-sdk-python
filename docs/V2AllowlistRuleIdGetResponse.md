# V2AllowlistRuleIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**records** | [**List[AlertserviceAllowAlertNotifcationListRecord]**](AlertserviceAllowAlertNotifcationListRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_allowlist_rule_id_get_response import V2AllowlistRuleIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AllowlistRuleIdGetResponse from a JSON string
v2_allowlist_rule_id_get_response_instance = V2AllowlistRuleIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2AllowlistRuleIdGetResponse.to_json())

# convert the object into a dict
v2_allowlist_rule_id_get_response_dict = v2_allowlist_rule_id_get_response_instance.to_dict()
# create an instance of V2AllowlistRuleIdGetResponse from a dict
v2_allowlist_rule_id_get_response_from_dict = V2AllowlistRuleIdGetResponse.from_dict(v2_allowlist_rule_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



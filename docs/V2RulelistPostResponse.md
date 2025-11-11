# V2RulelistPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rule_list** | [**List[AlertserviceRuleRecord]**](AlertserviceRuleRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_rulelist_post_response import V2RulelistPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2RulelistPostResponse from a JSON string
v2_rulelist_post_response_instance = V2RulelistPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2RulelistPostResponse.to_json())

# convert the object into a dict
v2_rulelist_post_response_dict = v2_rulelist_post_response_instance.to_dict()
# create an instance of V2RulelistPostResponse from a dict
v2_rulelist_post_response_from_dict = V2RulelistPostResponse.from_dict(v2_rulelist_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



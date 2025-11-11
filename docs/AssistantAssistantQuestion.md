# AssistantAssistantQuestion


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**conversation_id** | **str** |  | [optional] 
**question_language** | **str** |  | [optional] 
**question_text** | **str** |  | [optional] 
**question_timestamp** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assistant_assistant_question import AssistantAssistantQuestion

# TODO update the JSON string below
json = "{}"
# create an instance of AssistantAssistantQuestion from a JSON string
assistant_assistant_question_instance = AssistantAssistantQuestion.from_json(json)
# print the JSON string representation of the object
print(AssistantAssistantQuestion.to_json())

# convert the object into a dict
assistant_assistant_question_dict = assistant_assistant_question_instance.to_dict()
# create an instance of AssistantAssistantQuestion from a dict
assistant_assistant_question_from_dict = AssistantAssistantQuestion.from_dict(assistant_assistant_question_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AssistantAssistantConversation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**conversation_header** | **str** |  | [optional] 
**conversation_id** | **str** |  | [optional] 
**conversation_recent_timestamp** | **int** |  | [optional] 
**enable_context_history** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assistant_assistant_conversation import AssistantAssistantConversation

# TODO update the JSON string below
json = "{}"
# create an instance of AssistantAssistantConversation from a JSON string
assistant_assistant_conversation_instance = AssistantAssistantConversation.from_json(json)
# print the JSON string representation of the object
print(AssistantAssistantConversation.to_json())

# convert the object into a dict
assistant_assistant_conversation_dict = assistant_assistant_conversation_instance.to_dict()
# create an instance of AssistantAssistantConversation from a dict
assistant_assistant_conversation_from_dict = AssistantAssistantConversation.from_dict(assistant_assistant_conversation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



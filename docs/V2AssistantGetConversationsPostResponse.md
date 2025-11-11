# V2AssistantGetConversationsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**conversation_list** | [**List[AssistantAssistantConversation]**](AssistantAssistantConversation.md) |  | [optional] 
**enable_context_history** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assistant_get_conversations_post_response import V2AssistantGetConversationsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssistantGetConversationsPostResponse from a JSON string
v2_assistant_get_conversations_post_response_instance = V2AssistantGetConversationsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssistantGetConversationsPostResponse.to_json())

# convert the object into a dict
v2_assistant_get_conversations_post_response_dict = v2_assistant_get_conversations_post_response_instance.to_dict()
# create an instance of V2AssistantGetConversationsPostResponse from a dict
v2_assistant_get_conversations_post_response_from_dict = V2AssistantGetConversationsPostResponse.from_dict(v2_assistant_get_conversations_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



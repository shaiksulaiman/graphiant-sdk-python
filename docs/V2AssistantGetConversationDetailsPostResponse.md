# V2AssistantGetConversationDetailsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**conversation_id** | **str** |  | [optional] 
**response_list** | [**List[AssistantAssistantResponse]**](AssistantAssistantResponse.md) |  | [optional] 
**user_id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assistant_get_conversation_details_post_response import V2AssistantGetConversationDetailsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssistantGetConversationDetailsPostResponse from a JSON string
v2_assistant_get_conversation_details_post_response_instance = V2AssistantGetConversationDetailsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssistantGetConversationDetailsPostResponse.to_json())

# convert the object into a dict
v2_assistant_get_conversation_details_post_response_dict = v2_assistant_get_conversation_details_post_response_instance.to_dict()
# create an instance of V2AssistantGetConversationDetailsPostResponse from a dict
v2_assistant_get_conversation_details_post_response_from_dict = V2AssistantGetConversationDetailsPostResponse.from_dict(v2_assistant_get_conversation_details_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



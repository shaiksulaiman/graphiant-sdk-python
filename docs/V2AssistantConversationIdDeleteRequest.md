# V2AssistantConversationIdDeleteRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**conversation_id_string** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assistant_conversation_id_delete_request import V2AssistantConversationIdDeleteRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssistantConversationIdDeleteRequest from a JSON string
v2_assistant_conversation_id_delete_request_instance = V2AssistantConversationIdDeleteRequest.from_json(json)
# print the JSON string representation of the object
print(V2AssistantConversationIdDeleteRequest.to_json())

# convert the object into a dict
v2_assistant_conversation_id_delete_request_dict = v2_assistant_conversation_id_delete_request_instance.to_dict()
# create an instance of V2AssistantConversationIdDeleteRequest from a dict
v2_assistant_conversation_id_delete_request_from_dict = V2AssistantConversationIdDeleteRequest.from_dict(v2_assistant_conversation_id_delete_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



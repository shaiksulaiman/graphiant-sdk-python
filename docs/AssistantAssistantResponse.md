# AssistantAssistantResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**conversation_id** | **str** |  | [optional] 
**dataframe_dictionary** | [**List[AssistantDataframeDictionary]**](AssistantDataframeDictionary.md) |  | [optional] 
**original_question** | [**AssistantAssistantQuestion**](AssistantAssistantQuestion.md) |  | [optional] 
**response_id** | **str** |  | [optional] 
**response_language** | **str** |  | [optional] 
**response_text** | **str** |  | [optional] 
**response_timestamp** | **int** |  | [optional] 
**response_type** | **str** |  | [optional] 
**visualization_summary** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assistant_assistant_response import AssistantAssistantResponse

# TODO update the JSON string below
json = "{}"
# create an instance of AssistantAssistantResponse from a JSON string
assistant_assistant_response_instance = AssistantAssistantResponse.from_json(json)
# print the JSON string representation of the object
print(AssistantAssistantResponse.to_json())

# convert the object into a dict
assistant_assistant_response_dict = assistant_assistant_response_instance.to_dict()
# create an instance of AssistantAssistantResponse from a dict
assistant_assistant_response_from_dict = AssistantAssistantResponse.from_dict(assistant_assistant_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



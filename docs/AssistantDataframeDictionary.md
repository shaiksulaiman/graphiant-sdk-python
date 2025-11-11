# AssistantDataframeDictionary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dataframe_dictionary_map** | **Dict[str, str]** |  | [optional] 
**x_axis** | **str** |  | [optional] 
**y_axis** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assistant_dataframe_dictionary import AssistantDataframeDictionary

# TODO update the JSON string below
json = "{}"
# create an instance of AssistantDataframeDictionary from a JSON string
assistant_dataframe_dictionary_instance = AssistantDataframeDictionary.from_json(json)
# print the JSON string representation of the object
print(AssistantDataframeDictionary.to_json())

# convert the object into a dict
assistant_dataframe_dictionary_dict = assistant_dataframe_dictionary_instance.to_dict()
# create an instance of AssistantDataframeDictionary from a dict
assistant_dataframe_dictionary_from_dict = AssistantDataframeDictionary.from_dict(assistant_dataframe_dictionary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



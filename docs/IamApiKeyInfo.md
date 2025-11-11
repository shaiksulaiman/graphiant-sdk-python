# IamApiKeyInfo


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expiry_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**gcs_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.iam_api_key_info import IamApiKeyInfo

# TODO update the JSON string below
json = "{}"
# create an instance of IamApiKeyInfo from a JSON string
iam_api_key_info_instance = IamApiKeyInfo.from_json(json)
# print the JSON string representation of the object
print(IamApiKeyInfo.to_json())

# convert the object into a dict
iam_api_key_info_dict = iam_api_key_info_instance.to_dict()
# create an instance of IamApiKeyInfo from a dict
iam_api_key_info_from_dict = IamApiKeyInfo.from_dict(iam_api_key_info_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



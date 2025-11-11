# V2ChildalertlistPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alert_list** | [**List[AlertserviceAlertRecord]**](AlertserviceAlertRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_childalertlist_post_response import V2ChildalertlistPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ChildalertlistPostResponse from a JSON string
v2_childalertlist_post_response_instance = V2ChildalertlistPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ChildalertlistPostResponse.to_json())

# convert the object into a dict
v2_childalertlist_post_response_dict = v2_childalertlist_post_response_instance.to_dict()
# create an instance of V2ChildalertlistPostResponse from a dict
v2_childalertlist_post_response_from_dict = V2ChildalertlistPostResponse.from_dict(v2_childalertlist_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



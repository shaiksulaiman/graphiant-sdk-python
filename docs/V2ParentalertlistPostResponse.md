# V2ParentalertlistPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alert_list** | [**List[AlertserviceAlertRecord]**](AlertserviceAlertRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_parentalertlist_post_response import V2ParentalertlistPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ParentalertlistPostResponse from a JSON string
v2_parentalertlist_post_response_instance = V2ParentalertlistPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ParentalertlistPostResponse.to_json())

# convert the object into a dict
v2_parentalertlist_post_response_dict = v2_parentalertlist_post_response_instance.to_dict()
# create an instance of V2ParentalertlistPostResponse from a dict
v2_parentalertlist_post_response_from_dict = V2ParentalertlistPostResponse.from_dict(v2_parentalertlist_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



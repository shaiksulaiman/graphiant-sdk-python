# V2ParentalertlistPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**time_window** | [**AlertserviceTimeWindow**](AlertserviceTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_parentalertlist_post_request import V2ParentalertlistPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2ParentalertlistPostRequest from a JSON string
v2_parentalertlist_post_request_instance = V2ParentalertlistPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2ParentalertlistPostRequest.to_json())

# convert the object into a dict
v2_parentalertlist_post_request_dict = v2_parentalertlist_post_request_instance.to_dict()
# create an instance of V2ParentalertlistPostRequest from a dict
v2_parentalertlist_post_request_from_dict = V2ParentalertlistPostRequest.from_dict(v2_parentalertlist_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



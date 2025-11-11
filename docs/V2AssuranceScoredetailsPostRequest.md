# V2AssuranceScoredetailsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**time_window** | [**AssuranceTimeWindow**](AssuranceTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_scoredetails_post_request import V2AssuranceScoredetailsPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceScoredetailsPostRequest from a JSON string
v2_assurance_scoredetails_post_request_instance = V2AssuranceScoredetailsPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceScoredetailsPostRequest.to_json())

# convert the object into a dict
v2_assurance_scoredetails_post_request_dict = v2_assurance_scoredetails_post_request_instance.to_dict()
# create an instance of V2AssuranceScoredetailsPostRequest from a dict
v2_assurance_scoredetails_post_request_from_dict = V2AssuranceScoredetailsPostRequest.from_dict(v2_assurance_scoredetails_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



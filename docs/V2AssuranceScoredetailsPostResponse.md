# V2AssuranceScoredetailsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**score_details** | [**AssuranceScoreDetails**](AssuranceScoreDetails.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_scoredetails_post_response import V2AssuranceScoredetailsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceScoredetailsPostResponse from a JSON string
v2_assurance_scoredetails_post_response_instance = V2AssuranceScoredetailsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceScoredetailsPostResponse.to_json())

# convert the object into a dict
v2_assurance_scoredetails_post_response_dict = v2_assurance_scoredetails_post_response_instance.to_dict()
# create an instance of V2AssuranceScoredetailsPostResponse from a dict
v2_assurance_scoredetails_post_response_from_dict = V2AssuranceScoredetailsPostResponse.from_dict(v2_assurance_scoredetails_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



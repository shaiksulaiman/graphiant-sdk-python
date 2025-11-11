# V2AssuranceEnterprisesummaryPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**time_window** | [**AssuranceTimeWindow**](AssuranceTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_enterprisesummary_post_request import V2AssuranceEnterprisesummaryPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceEnterprisesummaryPostRequest from a JSON string
v2_assurance_enterprisesummary_post_request_instance = V2AssuranceEnterprisesummaryPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceEnterprisesummaryPostRequest.to_json())

# convert the object into a dict
v2_assurance_enterprisesummary_post_request_dict = v2_assurance_enterprisesummary_post_request_instance.to_dict()
# create an instance of V2AssuranceEnterprisesummaryPostRequest from a dict
v2_assurance_enterprisesummary_post_request_from_dict = V2AssuranceEnterprisesummaryPostRequest.from_dict(v2_assurance_enterprisesummary_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



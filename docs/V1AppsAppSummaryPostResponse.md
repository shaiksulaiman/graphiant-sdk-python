# V1AppsAppSummaryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_summary** | [**IpfixAppStateSummaryCount**](IpfixAppStateSummaryCount.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_apps_app_summary_post_response import V1AppsAppSummaryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AppsAppSummaryPostResponse from a JSON string
v1_apps_app_summary_post_response_instance = V1AppsAppSummaryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AppsAppSummaryPostResponse.to_json())

# convert the object into a dict
v1_apps_app_summary_post_response_dict = v1_apps_app_summary_post_response_instance.to_dict()
# create an instance of V1AppsAppSummaryPostResponse from a dict
v1_apps_app_summary_post_response_from_dict = V1AppsAppSummaryPostResponse.from_dict(v1_apps_app_summary_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



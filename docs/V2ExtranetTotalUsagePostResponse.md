# V2ExtranetTotalUsagePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**usage** | **float** | total service usage in kilo bytes | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranet_total_usage_post_response import V2ExtranetTotalUsagePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetTotalUsagePostResponse from a JSON string
v2_extranet_total_usage_post_response_instance = V2ExtranetTotalUsagePostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetTotalUsagePostResponse.to_json())

# convert the object into a dict
v2_extranet_total_usage_post_response_dict = v2_extranet_total_usage_post_response_instance.to_dict()
# create an instance of V2ExtranetTotalUsagePostResponse from a dict
v2_extranet_total_usage_post_response_from_dict = V2ExtranetTotalUsagePostResponse.from_dict(v2_extranet_total_usage_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



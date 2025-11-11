# V1AppsSiteSiteIdTopPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apps_utilization** | [**List[IpfixAppUtilizationSummary]**](IpfixAppUtilizationSummary.md) |  | [optional] 
**total_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_apps_site_site_id_top_post_response import V1AppsSiteSiteIdTopPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AppsSiteSiteIdTopPostResponse from a JSON string
v1_apps_site_site_id_top_post_response_instance = V1AppsSiteSiteIdTopPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AppsSiteSiteIdTopPostResponse.to_json())

# convert the object into a dict
v1_apps_site_site_id_top_post_response_dict = v1_apps_site_site_id_top_post_response_instance.to_dict()
# create an instance of V1AppsSiteSiteIdTopPostResponse from a dict
v1_apps_site_site_id_top_post_response_from_dict = V1AppsSiteSiteIdTopPostResponse.from_dict(v1_apps_site_site_id_top_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



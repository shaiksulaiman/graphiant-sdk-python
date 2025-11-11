# V1AppsSiteSiteIdTopPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**num_apps** | **int** | The maximum number of apps to return (100 if left empty) | [optional] 
**time_window** | [**IpfixTimeWindow**](IpfixTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_apps_site_site_id_top_post_request import V1AppsSiteSiteIdTopPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1AppsSiteSiteIdTopPostRequest from a JSON string
v1_apps_site_site_id_top_post_request_instance = V1AppsSiteSiteIdTopPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1AppsSiteSiteIdTopPostRequest.to_json())

# convert the object into a dict
v1_apps_site_site_id_top_post_request_dict = v1_apps_site_site_id_top_post_request_instance.to_dict()
# create an instance of V1AppsSiteSiteIdTopPostRequest from a dict
v1_apps_site_site_id_top_post_request_from_dict = V1AppsSiteSiteIdTopPostRequest.from_dict(v1_apps_site_site_id_top_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



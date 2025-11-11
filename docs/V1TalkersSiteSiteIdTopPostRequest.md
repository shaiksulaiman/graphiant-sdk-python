# V1TalkersSiteSiteIdTopPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**num_clients** | **int** | The maximum number of apps to return (10 if left empty) | [optional] 
**time_window** | [**IpfixTimeWindow**](IpfixTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_talkers_site_site_id_top_post_request import V1TalkersSiteSiteIdTopPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1TalkersSiteSiteIdTopPostRequest from a JSON string
v1_talkers_site_site_id_top_post_request_instance = V1TalkersSiteSiteIdTopPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1TalkersSiteSiteIdTopPostRequest.to_json())

# convert the object into a dict
v1_talkers_site_site_id_top_post_request_dict = v1_talkers_site_site_id_top_post_request_instance.to_dict()
# create an instance of V1TalkersSiteSiteIdTopPostRequest from a dict
v1_talkers_site_site_id_top_post_request_from_dict = V1TalkersSiteSiteIdTopPostRequest.from_dict(v1_talkers_site_site_id_top_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



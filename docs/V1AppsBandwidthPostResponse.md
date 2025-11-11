# V1AppsBandwidthPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**stats** | [**List[IpfixAppBandwidthStats]**](IpfixAppBandwidthStats.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_apps_bandwidth_post_response import V1AppsBandwidthPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1AppsBandwidthPostResponse from a JSON string
v1_apps_bandwidth_post_response_instance = V1AppsBandwidthPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1AppsBandwidthPostResponse.to_json())

# convert the object into a dict
v1_apps_bandwidth_post_response_dict = v1_apps_bandwidth_post_response_instance.to_dict()
# create an instance of V1AppsBandwidthPostResponse from a dict
v1_apps_bandwidth_post_response_from_dict = V1AppsBandwidthPostResponse.from_dict(v1_apps_bandwidth_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



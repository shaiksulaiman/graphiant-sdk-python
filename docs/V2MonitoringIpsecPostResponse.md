# V2MonitoringIpsecPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[V2MonitoringIpsecPostResponseData]**](V2MonitoringIpsecPostResponseData.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_ipsec_post_response import V2MonitoringIpsecPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringIpsecPostResponse from a JSON string
v2_monitoring_ipsec_post_response_instance = V2MonitoringIpsecPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringIpsecPostResponse.to_json())

# convert the object into a dict
v2_monitoring_ipsec_post_response_dict = v2_monitoring_ipsec_post_response_instance.to_dict()
# create an instance of V2MonitoringIpsecPostResponse from a dict
v2_monitoring_ipsec_post_response_from_dict = V2MonitoringIpsecPostResponse.from_dict(v2_monitoring_ipsec_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V2MonitoringExtranetLogDetailsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**logs** | [**List[V2MonitoringExtranetLogDetailsPostResponseLogDetails]**](V2MonitoringExtranetLogDetailsPostResponseLogDetails.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_extranet_log_details_post_response import V2MonitoringExtranetLogDetailsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringExtranetLogDetailsPostResponse from a JSON string
v2_monitoring_extranet_log_details_post_response_instance = V2MonitoringExtranetLogDetailsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringExtranetLogDetailsPostResponse.to_json())

# convert the object into a dict
v2_monitoring_extranet_log_details_post_response_dict = v2_monitoring_extranet_log_details_post_response_instance.to_dict()
# create an instance of V2MonitoringExtranetLogDetailsPostResponse from a dict
v2_monitoring_extranet_log_details_post_response_from_dict = V2MonitoringExtranetLogDetailsPostResponse.from_dict(v2_monitoring_extranet_log_details_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



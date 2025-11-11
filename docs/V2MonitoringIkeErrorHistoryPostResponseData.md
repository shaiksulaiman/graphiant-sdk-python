# V2MonitoringIkeErrorHistoryPostResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_address** | **str** |  | [optional] 
**destination_port** | **str** |  | [optional] 
**error_type** | **str** |  | [optional] 
**message** | **str** |  | [optional] 
**timestamp** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**tunnel_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_ike_error_history_post_response_data import V2MonitoringIkeErrorHistoryPostResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringIkeErrorHistoryPostResponseData from a JSON string
v2_monitoring_ike_error_history_post_response_data_instance = V2MonitoringIkeErrorHistoryPostResponseData.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringIkeErrorHistoryPostResponseData.to_json())

# convert the object into a dict
v2_monitoring_ike_error_history_post_response_data_dict = v2_monitoring_ike_error_history_post_response_data_instance.to_dict()
# create an instance of V2MonitoringIkeErrorHistoryPostResponseData from a dict
v2_monitoring_ike_error_history_post_response_data_from_dict = V2MonitoringIkeErrorHistoryPostResponseData.from_dict(v2_monitoring_ike_error_history_post_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



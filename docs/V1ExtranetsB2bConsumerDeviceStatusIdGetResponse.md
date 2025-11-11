# V1ExtranetsB2bConsumerDeviceStatusIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**service_status** | **str** |  | [optional] 
**summary** | [**List[ManaV2B2bExtranetStatusSummary]**](ManaV2B2bExtranetStatusSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_consumer_device_status_id_get_response import V1ExtranetsB2bConsumerDeviceStatusIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bConsumerDeviceStatusIdGetResponse from a JSON string
v1_extranets_b2b_consumer_device_status_id_get_response_instance = V1ExtranetsB2bConsumerDeviceStatusIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bConsumerDeviceStatusIdGetResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_consumer_device_status_id_get_response_dict = v1_extranets_b2b_consumer_device_status_id_get_response_instance.to_dict()
# create an instance of V1ExtranetsB2bConsumerDeviceStatusIdGetResponse from a dict
v1_extranets_b2b_consumer_device_status_id_get_response_from_dict = V1ExtranetsB2bConsumerDeviceStatusIdGetResponse.from_dict(v1_extranets_b2b_consumer_device_status_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesSummaryGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sites** | [**List[V1DevicesSummaryGetResponseSiteSummary]**](V1DevicesSummaryGetResponseSiteSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_summary_get_response import V1DevicesSummaryGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesSummaryGetResponse from a JSON string
v1_devices_summary_get_response_instance = V1DevicesSummaryGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesSummaryGetResponse.to_json())

# convert the object into a dict
v1_devices_summary_get_response_dict = v1_devices_summary_get_response_instance.to_dict()
# create an instance of V1DevicesSummaryGetResponse from a dict
v1_devices_summary_get_response_from_dict = V1DevicesSummaryGetResponse.from_dict(v1_devices_summary_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



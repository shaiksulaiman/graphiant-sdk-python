# V1DevicesSummaryGetResponseSiteSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[V1DevicesSummaryGetResponseSiteSummaryDeviceSummary]**](V1DevicesSummaryGetResponseSiteSummaryDeviceSummary.md) |  | [optional] 
**site_id** | **int** |  | [optional] 
**site_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_summary_get_response_site_summary import V1DevicesSummaryGetResponseSiteSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesSummaryGetResponseSiteSummary from a JSON string
v1_devices_summary_get_response_site_summary_instance = V1DevicesSummaryGetResponseSiteSummary.from_json(json)
# print the JSON string representation of the object
print(V1DevicesSummaryGetResponseSiteSummary.to_json())

# convert the object into a dict
v1_devices_summary_get_response_site_summary_dict = v1_devices_summary_get_response_site_summary_instance.to_dict()
# create an instance of V1DevicesSummaryGetResponseSiteSummary from a dict
v1_devices_summary_get_response_site_summary_from_dict = V1DevicesSummaryGetResponseSiteSummary.from_dict(v1_devices_summary_get_response_site_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



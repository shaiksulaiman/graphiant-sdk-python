# V1DevicesSummaryGetResponseSiteSummaryDeviceSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**is_virtual** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**override_region** | [**ManaV2Region**](ManaV2Region.md) |  | [optional] 
**platform_name** | **str** |  | [optional] 
**region** | [**ManaV2Region**](ManaV2Region.md) |  | [optional] 
**role** | **str** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_summary_get_response_site_summary_device_summary import V1DevicesSummaryGetResponseSiteSummaryDeviceSummary

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesSummaryGetResponseSiteSummaryDeviceSummary from a JSON string
v1_devices_summary_get_response_site_summary_device_summary_instance = V1DevicesSummaryGetResponseSiteSummaryDeviceSummary.from_json(json)
# print the JSON string representation of the object
print(V1DevicesSummaryGetResponseSiteSummaryDeviceSummary.to_json())

# convert the object into a dict
v1_devices_summary_get_response_site_summary_device_summary_dict = v1_devices_summary_get_response_site_summary_device_summary_instance.to_dict()
# create an instance of V1DevicesSummaryGetResponseSiteSummaryDeviceSummary from a dict
v1_devices_summary_get_response_site_summary_device_summary_from_dict = V1DevicesSummaryGetResponseSiteSummaryDeviceSummary.from_dict(v1_devices_summary_get_response_site_summary_device_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



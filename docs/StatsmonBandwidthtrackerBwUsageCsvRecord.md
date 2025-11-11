# StatsmonBandwidthtrackerBwUsageCsvRecord


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloud_provider_name** | **str** |  | [optional] 
**device_id** | **int** |  | [optional] 
**enterprise_id** | **int** |  | [optional] 
**region_name** | **str** |  | [optional] 
**service_type** | **int** |  | [optional] 
**site_id** | **int** |  | [optional] 
**usage_kbps** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_bandwidthtracker_bw_usage_csv_record import StatsmonBandwidthtrackerBwUsageCsvRecord

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonBandwidthtrackerBwUsageCsvRecord from a JSON string
statsmon_bandwidthtracker_bw_usage_csv_record_instance = StatsmonBandwidthtrackerBwUsageCsvRecord.from_json(json)
# print the JSON string representation of the object
print(StatsmonBandwidthtrackerBwUsageCsvRecord.to_json())

# convert the object into a dict
statsmon_bandwidthtracker_bw_usage_csv_record_dict = statsmon_bandwidthtracker_bw_usage_csv_record_instance.to_dict()
# create an instance of StatsmonBandwidthtrackerBwUsageCsvRecord from a dict
statsmon_bandwidthtracker_bw_usage_csv_record_from_dict = StatsmonBandwidthtrackerBwUsageCsvRecord.from_dict(statsmon_bandwidthtracker_bw_usage_csv_record_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1BwtrackerSiteGatewayCsvPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**region_id** | **int** |  | [optional] 
**site_id** | **int** |  | [optional] 
**time_window** | [**StatsmonBandwidthtrackerTimeWindow**](StatsmonBandwidthtrackerTimeWindow.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_bwtracker_site_gateway_csv_post_request import V1BwtrackerSiteGatewayCsvPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1BwtrackerSiteGatewayCsvPostRequest from a JSON string
v1_bwtracker_site_gateway_csv_post_request_instance = V1BwtrackerSiteGatewayCsvPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1BwtrackerSiteGatewayCsvPostRequest.to_json())

# convert the object into a dict
v1_bwtracker_site_gateway_csv_post_request_dict = v1_bwtracker_site_gateway_csv_post_request_instance.to_dict()
# create an instance of V1BwtrackerSiteGatewayCsvPostRequest from a dict
v1_bwtracker_site_gateway_csv_post_request_from_dict = V1BwtrackerSiteGatewayCsvPostRequest.from_dict(v1_bwtracker_site_gateway_csv_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



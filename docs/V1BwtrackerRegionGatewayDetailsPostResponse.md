# V1BwtrackerRegionGatewayDetailsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bwusage_details** | [**StatsmonBandwidthtrackerBwUsageByRegionEdgeDetails**](StatsmonBandwidthtrackerBwUsageByRegionEdgeDetails.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_bwtracker_region_gateway_details_post_response import V1BwtrackerRegionGatewayDetailsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1BwtrackerRegionGatewayDetailsPostResponse from a JSON string
v1_bwtracker_region_gateway_details_post_response_instance = V1BwtrackerRegionGatewayDetailsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1BwtrackerRegionGatewayDetailsPostResponse.to_json())

# convert the object into a dict
v1_bwtracker_region_gateway_details_post_response_dict = v1_bwtracker_region_gateway_details_post_response_instance.to_dict()
# create an instance of V1BwtrackerRegionGatewayDetailsPostResponse from a dict
v1_bwtracker_region_gateway_details_post_response_from_dict = V1BwtrackerRegionGatewayDetailsPostResponse.from_dict(v1_bwtracker_region_gateway_details_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



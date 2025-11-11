# V2ExtranetSitesUsagePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | the id associated with an entity - consumer_id for consumer, and service_id for the producer/service | [optional] 
**is_b2_b** | **bool** |  | [optional] 
**is_provider** | **bool** |  | [optional] 
**service_id** | **int** |  | [optional] 
**site_id** | **int** |  | [optional] 
**subscription_name** | **str** | Optional subscription name for filter | [optional] 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | [optional] 
**vrf_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranet_sites_usage_post_request import V2ExtranetSitesUsagePostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetSitesUsagePostRequest from a JSON string
v2_extranet_sites_usage_post_request_instance = V2ExtranetSitesUsagePostRequest.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetSitesUsagePostRequest.to_json())

# convert the object into a dict
v2_extranet_sites_usage_post_request_dict = v2_extranet_sites_usage_post_request_instance.to_dict()
# create an instance of V2ExtranetSitesUsagePostRequest from a dict
v2_extranet_sites_usage_post_request_from_dict = V2ExtranetSitesUsagePostRequest.from_dict(v2_extranet_sites_usage_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



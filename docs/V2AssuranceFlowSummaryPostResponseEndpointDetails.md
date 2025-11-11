# V2AssuranceFlowSummaryPostResponseEndpointDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuits** | **List[str]** |  | [optional] 
**edges** | [**List[AssuranceEdge]**](AssuranceEdge.md) |  | [optional] 
**jitter** | [**V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics**](V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics.md) |  | [optional] 
**latency** | [**V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics**](V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics.md) |  | [optional] 
**loss** | [**V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics**](V2AssuranceFlowSummaryPostResponseEndpointDetailsStatistics.md) |  | [optional] 
**site** | [**AssuranceSite**](AssuranceSite.md) |  | [optional] 
**total_downlink_usage** | **int** |  | [optional] 
**total_uplink_usage** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_flow_summary_post_response_endpoint_details import V2AssuranceFlowSummaryPostResponseEndpointDetails

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceFlowSummaryPostResponseEndpointDetails from a JSON string
v2_assurance_flow_summary_post_response_endpoint_details_instance = V2AssuranceFlowSummaryPostResponseEndpointDetails.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceFlowSummaryPostResponseEndpointDetails.to_json())

# convert the object into a dict
v2_assurance_flow_summary_post_response_endpoint_details_dict = v2_assurance_flow_summary_post_response_endpoint_details_instance.to_dict()
# create an instance of V2AssuranceFlowSummaryPostResponseEndpointDetails from a dict
v2_assurance_flow_summary_post_response_endpoint_details_from_dict = V2AssuranceFlowSummaryPostResponseEndpointDetails.from_dict(v2_assurance_flow_summary_post_response_endpoint_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



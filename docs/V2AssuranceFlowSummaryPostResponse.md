# V2AssuranceFlowSummaryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**app_name** | **str** |  | [optional] 
**bucket** | **str** |  | [optional] 
**client_endpoint** | [**V2AssuranceFlowSummaryPostResponseEndpointDetails**](V2AssuranceFlowSummaryPostResponseEndpointDetails.md) |  | [optional] 
**client_ip** | **str** |  | [optional] 
**first_seen_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**lan_segment** | **str** |  | [optional] 
**last_seen_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**risk_status** | **str** |  | [optional] 
**server_endpoint** | [**V2AssuranceFlowSummaryPostResponseEndpointDetails**](V2AssuranceFlowSummaryPostResponseEndpointDetails.md) |  | [optional] 
**server_ip** | **str** |  | [optional] 
**server_port** | **int** |  | [optional] 
**sla_class** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_flow_summary_post_response import V2AssuranceFlowSummaryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceFlowSummaryPostResponse from a JSON string
v2_assurance_flow_summary_post_response_instance = V2AssuranceFlowSummaryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceFlowSummaryPostResponse.to_json())

# convert the object into a dict
v2_assurance_flow_summary_post_response_dict = v2_assurance_flow_summary_post_response_instance.to_dict()
# create an instance of V2AssuranceFlowSummaryPostResponse from a dict
v2_assurance_flow_summary_post_response_from_dict = V2AssuranceFlowSummaryPostResponse.from_dict(v2_assurance_flow_summary_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



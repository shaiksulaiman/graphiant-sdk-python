# AssuranceClientSessionEndpointDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuits** | **List[str]** |  | [optional] 
**edges** | [**List[AssuranceEdge]**](AssuranceEdge.md) |  | [optional] 
**is_gateway** | **bool** |  | [optional] 
**jitter** | [**AssuranceClientSessionEndpointDetailsStatistics**](AssuranceClientSessionEndpointDetailsStatistics.md) |  | [optional] 
**latency** | [**AssuranceClientSessionEndpointDetailsStatistics**](AssuranceClientSessionEndpointDetailsStatistics.md) |  | [optional] 
**loss** | [**AssuranceClientSessionEndpointDetailsStatistics**](AssuranceClientSessionEndpointDetailsStatistics.md) |  | [optional] 
**site** | [**AssuranceSite**](AssuranceSite.md) |  | [optional] 
**total_downlink_usage** | **int** |  | [optional] 
**total_uplink_usage** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_client_session_endpoint_details import AssuranceClientSessionEndpointDetails

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceClientSessionEndpointDetails from a JSON string
assurance_client_session_endpoint_details_instance = AssuranceClientSessionEndpointDetails.from_json(json)
# print the JSON string representation of the object
print(AssuranceClientSessionEndpointDetails.to_json())

# convert the object into a dict
assurance_client_session_endpoint_details_dict = assurance_client_session_endpoint_details_instance.to_dict()
# create an instance of AssuranceClientSessionEndpointDetails from a dict
assurance_client_session_endpoint_details_from_dict = AssuranceClientSessionEndpointDetails.from_dict(assurance_client_session_endpoint_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



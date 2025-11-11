# V2AssuranceEndpointIntelPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**am_categories** | **List[str]** |  | [optional] 
**am_risk_score** | **float** |  | [optional] 
**graphiant_risky** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_endpoint_intel_post_response import V2AssuranceEndpointIntelPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceEndpointIntelPostResponse from a JSON string
v2_assurance_endpoint_intel_post_response_instance = V2AssuranceEndpointIntelPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceEndpointIntelPostResponse.to_json())

# convert the object into a dict
v2_assurance_endpoint_intel_post_response_dict = v2_assurance_endpoint_intel_post_response_instance.to_dict()
# create an instance of V2AssuranceEndpointIntelPostResponse from a dict
v2_assurance_endpoint_intel_post_response_from_dict = V2AssuranceEndpointIntelPostResponse.from_dict(v2_assurance_endpoint_intel_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



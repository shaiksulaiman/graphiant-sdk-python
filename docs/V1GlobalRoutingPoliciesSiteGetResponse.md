# V1GlobalRoutingPoliciesSiteGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**routing_policies** | [**List[ManaV2RoutingPolicy]**](ManaV2RoutingPolicy.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_routing_policies_site_get_response import V1GlobalRoutingPoliciesSiteGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalRoutingPoliciesSiteGetResponse from a JSON string
v1_global_routing_policies_site_get_response_instance = V1GlobalRoutingPoliciesSiteGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalRoutingPoliciesSiteGetResponse.to_json())

# convert the object into a dict
v1_global_routing_policies_site_get_response_dict = v1_global_routing_policies_site_get_response_instance.to_dict()
# create an instance of V1GlobalRoutingPoliciesSiteGetResponse from a dict
v1_global_routing_policies_site_get_response_from_dict = V1GlobalRoutingPoliciesSiteGetResponse.from_dict(v1_global_routing_policies_site_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



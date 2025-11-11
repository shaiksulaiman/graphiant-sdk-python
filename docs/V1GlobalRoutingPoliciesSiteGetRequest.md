# V1GlobalRoutingPoliciesSiteGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_routing_policies_site_get_request import V1GlobalRoutingPoliciesSiteGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalRoutingPoliciesSiteGetRequest from a JSON string
v1_global_routing_policies_site_get_request_instance = V1GlobalRoutingPoliciesSiteGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalRoutingPoliciesSiteGetRequest.to_json())

# convert the object into a dict
v1_global_routing_policies_site_get_request_dict = v1_global_routing_policies_site_get_request_instance.to_dict()
# create an instance of V1GlobalRoutingPoliciesSiteGetRequest from a dict
v1_global_routing_policies_site_get_request_from_dict = V1GlobalRoutingPoliciesSiteGetRequest.from_dict(v1_global_routing_policies_site_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



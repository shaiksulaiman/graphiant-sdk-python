# V1PolicyRouteTagSetsTagDetailGetRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tag** | [**ManaV2RouteTagId**](ManaV2RouteTagId.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_route_tag_sets_tag_detail_get_request import V1PolicyRouteTagSetsTagDetailGetRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyRouteTagSetsTagDetailGetRequest from a JSON string
v1_policy_route_tag_sets_tag_detail_get_request_instance = V1PolicyRouteTagSetsTagDetailGetRequest.from_json(json)
# print the JSON string representation of the object
print(V1PolicyRouteTagSetsTagDetailGetRequest.to_json())

# convert the object into a dict
v1_policy_route_tag_sets_tag_detail_get_request_dict = v1_policy_route_tag_sets_tag_detail_get_request_instance.to_dict()
# create an instance of V1PolicyRouteTagSetsTagDetailGetRequest from a dict
v1_policy_route_tag_sets_tag_detail_get_request_from_dict = V1PolicyRouteTagSetsTagDetailGetRequest.from_dict(v1_policy_route_tag_sets_tag_detail_get_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1PolicyRouteTagSetsTagDetailGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**devices** | [**List[ManaV2RouteTagDevice]**](ManaV2RouteTagDevice.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_policy_route_tag_sets_tag_detail_get_response import V1PolicyRouteTagSetsTagDetailGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1PolicyRouteTagSetsTagDetailGetResponse from a JSON string
v1_policy_route_tag_sets_tag_detail_get_response_instance = V1PolicyRouteTagSetsTagDetailGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1PolicyRouteTagSetsTagDetailGetResponse.to_json())

# convert the object into a dict
v1_policy_route_tag_sets_tag_detail_get_response_dict = v1_policy_route_tag_sets_tag_detail_get_response_instance.to_dict()
# create an instance of V1PolicyRouteTagSetsTagDetailGetResponse from a dict
v1_policy_route_tag_sets_tag_detail_get_response_from_dict = V1PolicyRouteTagSetsTagDetailGetResponse.from_dict(v1_policy_route_tag_sets_tag_detail_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



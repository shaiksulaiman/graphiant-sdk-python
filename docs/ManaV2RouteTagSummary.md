# ManaV2RouteTagSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_count** | **int** |  | [optional] 
**level_one** | **int** |  | [optional] 
**level_one_tag** | **str** |  | [optional] 
**level_two** | **int** |  | [optional] 
**level_two_tag** | **str** |  | [optional] 
**level_zero** | **int** |  | [optional] 
**level_zero_tag** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_route_tag_summary import ManaV2RouteTagSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2RouteTagSummary from a JSON string
mana_v2_route_tag_summary_instance = ManaV2RouteTagSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2RouteTagSummary.to_json())

# convert the object into a dict
mana_v2_route_tag_summary_dict = mana_v2_route_tag_summary_instance.to_dict()
# create an instance of ManaV2RouteTagSummary from a dict
mana_v2_route_tag_summary_from_dict = ManaV2RouteTagSummary.from_dict(mana_v2_route_tag_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2GlobalObjectServiceSummaries


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**routing_policies** | [**List[ManaV2GlobalObjectSummary]**](ManaV2GlobalObjectSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_global_object_service_summaries import ManaV2GlobalObjectServiceSummaries

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2GlobalObjectServiceSummaries from a JSON string
mana_v2_global_object_service_summaries_instance = ManaV2GlobalObjectServiceSummaries.from_json(json)
# print the JSON string representation of the object
print(ManaV2GlobalObjectServiceSummaries.to_json())

# convert the object into a dict
mana_v2_global_object_service_summaries_dict = mana_v2_global_object_service_summaries_instance.to_dict()
# create an instance of ManaV2GlobalObjectServiceSummaries from a dict
mana_v2_global_object_service_summaries_from_dict = ManaV2GlobalObjectServiceSummaries.from_dict(mana_v2_global_object_service_summaries_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



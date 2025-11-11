# ManaV2B2bExtranetConsumersSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**b2b_status** | **str** |  | [optional] 
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**id** | **int** |  | [optional] 
**num_edges** | **int** |  | [optional] 
**num_segments** | **int** |  | [optional] 
**num_sites** | **int** |  | [optional] 
**provider_name** | **str** |  | [optional] 
**publisher_name** | **str** |  | [optional] 
**service_name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_consumers_summary import ManaV2B2bExtranetConsumersSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetConsumersSummary from a JSON string
mana_v2_b2b_extranet_consumers_summary_instance = ManaV2B2bExtranetConsumersSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetConsumersSummary.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_consumers_summary_dict = mana_v2_b2b_extranet_consumers_summary_instance.to_dict()
# create an instance of ManaV2B2bExtranetConsumersSummary from a dict
mana_v2_b2b_extranet_consumers_summary_from_dict = ManaV2B2bExtranetConsumersSummary.from_dict(mana_v2_b2b_extranet_consumers_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ManaV2B2bExtranetStatusSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**device_id** | **int** |  | [optional] 
**device_status** | **str** |  | [optional] 
**location** | **int** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_status_summary import ManaV2B2bExtranetStatusSummary

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetStatusSummary from a JSON string
mana_v2_b2b_extranet_status_summary_instance = ManaV2B2bExtranetStatusSummary.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetStatusSummary.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_status_summary_dict = mana_v2_b2b_extranet_status_summary_instance.to_dict()
# create an instance of ManaV2B2bExtranetStatusSummary from a dict
mana_v2_b2b_extranet_status_summary_from_dict = ManaV2B2bExtranetStatusSummary.from_dict(mana_v2_b2b_extranet_status_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



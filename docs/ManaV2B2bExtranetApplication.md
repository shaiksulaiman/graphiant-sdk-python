# ManaV2B2bExtranetApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**id** | **int** |  | [optional] 
**is_publisher** | **bool** |  | [optional] 
**lan_segment** | **int** |  | [optional] 
**matched_customers** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**server_ip_address** | **List[str]** |  | [optional] 
**status** | **str** |  | [optional] 
**total_customers** | **int** |  | [optional] 
**total_sites** | **int** |  | [optional] 
**type** | **str** |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_application import ManaV2B2bExtranetApplication

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetApplication from a JSON string
mana_v2_b2b_extranet_application_instance = ManaV2B2bExtranetApplication.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetApplication.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_application_dict = mana_v2_b2b_extranet_application_instance.to_dict()
# create an instance of ManaV2B2bExtranetApplication from a dict
mana_v2_b2b_extranet_application_from_dict = ManaV2B2bExtranetApplication.from_dict(mana_v2_b2b_extranet_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



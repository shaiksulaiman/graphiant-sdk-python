# ManaV2IpfixExporter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_address** | **str** |  | [optional] 
**destination_port** | **int** |  | [optional] 
**error_message** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**monitored_segments** | **List[str]** |  | [optional] 
**name** | **str** |  | [optional] 
**sample_mode** | **str** |  | [optional] 
**sample_rate** | **int** |  | [optional] 
**source_address** | **str** |  | [optional] 
**source_interface** | **str** |  | [optional] 
**source_segment** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**vrf_id** | **int** |  | [optional] 
**vrf_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ipfix_exporter import ManaV2IpfixExporter

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IpfixExporter from a JSON string
mana_v2_ipfix_exporter_instance = ManaV2IpfixExporter.from_json(json)
# print the JSON string representation of the object
print(ManaV2IpfixExporter.to_json())

# convert the object into a dict
mana_v2_ipfix_exporter_dict = mana_v2_ipfix_exporter_instance.to_dict()
# create an instance of ManaV2IpfixExporter from a dict
mana_v2_ipfix_exporter_from_dict = ManaV2IpfixExporter.from_dict(mana_v2_ipfix_exporter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



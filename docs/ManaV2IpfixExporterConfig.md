# ManaV2IpfixExporterConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_address** | **str** |  | [optional] 
**destination_port** | **int** |  | [optional] 
**global_id** | **int** |  | [optional] 
**is_global_sync** | **bool** |  | [optional] 
**monitored_segments** | **List[str]** |  | [optional] 
**name** | **str** |  | [optional] 
**sample_mode** | **str** |  | [optional] 
**sample_rate** | **int** |  | [optional] 
**source_interface_name** | **str** |  | [optional] 
**vrf_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ipfix_exporter_config import ManaV2IpfixExporterConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IpfixExporterConfig from a JSON string
mana_v2_ipfix_exporter_config_instance = ManaV2IpfixExporterConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2IpfixExporterConfig.to_json())

# convert the object into a dict
mana_v2_ipfix_exporter_config_dict = mana_v2_ipfix_exporter_config_instance.to_dict()
# create an instance of ManaV2IpfixExporterConfig from a dict
mana_v2_ipfix_exporter_config_from_dict = ManaV2IpfixExporterConfig.from_dict(mana_v2_ipfix_exporter_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



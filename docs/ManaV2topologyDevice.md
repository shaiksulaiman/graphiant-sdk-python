# ManaV2topologyDevice


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**location** | **str** |  | [optional] 
**maintenance_mode** | **bool** |  | [optional] 
**management_ip** | **str** |  | [optional] 
**model** | **str** |  | [optional] 
**role** | **str** |  | [optional] 
**serial_number** | **str** |  | [optional] 
**site_id** | **int** |  | [optional] 
**software_version** | **str** |  | [optional] 
**staging_mode** | **bool** |  | [optional] 
**uptime** | [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 
**vrrp_interface** | **str** |  | [optional] 
**vrrp_state** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2topology_device import ManaV2topologyDevice

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2topologyDevice from a JSON string
mana_v2topology_device_instance = ManaV2topologyDevice.from_json(json)
# print the JSON string representation of the object
print(ManaV2topologyDevice.to_json())

# convert the object into a dict
mana_v2topology_device_dict = mana_v2topology_device_instance.to_dict()
# create an instance of ManaV2topologyDevice from a dict
mana_v2topology_device_from_dict = ManaV2topologyDevice.from_dict(mana_v2topology_device_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



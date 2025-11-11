# ManaV2PrometheusSysDbMonitorConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interval_seconds** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**xpaths** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prometheus_sys_db_monitor_config import ManaV2PrometheusSysDbMonitorConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrometheusSysDbMonitorConfig from a JSON string
mana_v2_prometheus_sys_db_monitor_config_instance = ManaV2PrometheusSysDbMonitorConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrometheusSysDbMonitorConfig.to_json())

# convert the object into a dict
mana_v2_prometheus_sys_db_monitor_config_dict = mana_v2_prometheus_sys_db_monitor_config_instance.to_dict()
# create an instance of ManaV2PrometheusSysDbMonitorConfig from a dict
mana_v2_prometheus_sys_db_monitor_config_from_dict = ManaV2PrometheusSysDbMonitorConfig.from_dict(mana_v2_prometheus_sys_db_monitor_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



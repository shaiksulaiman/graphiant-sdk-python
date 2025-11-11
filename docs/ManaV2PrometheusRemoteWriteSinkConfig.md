# ManaV2PrometheusRemoteWriteSinkConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**host** | **str** |  | [optional] 
**path** | **str** |  | [optional] 
**port** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_prometheus_remote_write_sink_config import ManaV2PrometheusRemoteWriteSinkConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2PrometheusRemoteWriteSinkConfig from a JSON string
mana_v2_prometheus_remote_write_sink_config_instance = ManaV2PrometheusRemoteWriteSinkConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2PrometheusRemoteWriteSinkConfig.to_json())

# convert the object into a dict
mana_v2_prometheus_remote_write_sink_config_dict = mana_v2_prometheus_remote_write_sink_config_instance.to_dict()
# create an instance of ManaV2PrometheusRemoteWriteSinkConfig from a dict
mana_v2_prometheus_remote_write_sink_config_from_dict = ManaV2PrometheusRemoteWriteSinkConfig.from_dict(mana_v2_prometheus_remote_write_sink_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



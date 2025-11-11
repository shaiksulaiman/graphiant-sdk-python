# IpfixTwampMetrics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**health_avg** | **str** | calculated health average (over time window)  | [optional] 
**jitter** | **float** | Jitter in ms | [optional] 
**latency** | **float** | Latency in  ms | [optional] 
**loss** | **float** | Loss in percentage | [optional] 
**mos** | **float** |  | [optional] 
**status** | **str** | calculated status (last measured value) | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_twamp_metrics import IpfixTwampMetrics

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixTwampMetrics from a JSON string
ipfix_twamp_metrics_instance = IpfixTwampMetrics.from_json(json)
# print the JSON string representation of the object
print(IpfixTwampMetrics.to_json())

# convert the object into a dict
ipfix_twamp_metrics_dict = ipfix_twamp_metrics_instance.to_dict()
# create an instance of IpfixTwampMetrics from a dict
ipfix_twamp_metrics_from_dict = IpfixTwampMetrics.from_dict(ipfix_twamp_metrics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# IpfixCircuitMetrics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | circuit name | [optional] 
**sla_class** | **str** |  | [optional] 
**stats** | [**IpfixTwampMetrics**](IpfixTwampMetrics.md) |  | [optional] 
**usage** | **float** | usage of the circuit by the application in kilo bytes | [optional] 
**usage_pct** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_circuit_metrics import IpfixCircuitMetrics

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixCircuitMetrics from a JSON string
ipfix_circuit_metrics_instance = IpfixCircuitMetrics.from_json(json)
# print the JSON string representation of the object
print(IpfixCircuitMetrics.to_json())

# convert the object into a dict
ipfix_circuit_metrics_dict = ipfix_circuit_metrics_instance.to_dict()
# create an instance of IpfixCircuitMetrics from a dict
ipfix_circuit_metrics_from_dict = IpfixCircuitMetrics.from_dict(ipfix_circuit_metrics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



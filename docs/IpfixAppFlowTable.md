# IpfixAppFlowTable


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dest_ip** | **str** |  | [optional] 
**dest_port** | **int** |  | [optional] 
**dl_circuit_name** | **str** |  | [optional] 
**dl_usage** | **float** | Down link application usage in MB | [optional] 
**egress_local_core_region** | **str** |  | [optional] 
**ingress_local_core_region** | **str** |  | [optional] 
**lan_segment** | **str** |  | [optional] 
**protocol** | **str** |  | [optional] 
**remote_core_region** | **str** |  | [optional] 
**sla_class** | **str** |  | [optional] 
**src_ip** | **str** |  | [optional] 
**src_port** | **int** |  | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ul_circuit_name** | **str** |  | [optional] 
**ul_usage** | **float** | Up link application usage in MB | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_app_flow_table import IpfixAppFlowTable

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixAppFlowTable from a JSON string
ipfix_app_flow_table_instance = IpfixAppFlowTable.from_json(json)
# print the JSON string representation of the object
print(IpfixAppFlowTable.to_json())

# convert the object into a dict
ipfix_app_flow_table_dict = ipfix_app_flow_table_instance.to_dict()
# create an instance of IpfixAppFlowTable from a dict
ipfix_app_flow_table_from_dict = IpfixAppFlowTable.from_dict(ipfix_app_flow_table_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



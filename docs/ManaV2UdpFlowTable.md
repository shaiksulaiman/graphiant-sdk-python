# ManaV2UdpFlowTable


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expiry** | **int** |  | [optional] 
**unidirectional_flow_limit** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_udp_flow_table import ManaV2UdpFlowTable

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2UdpFlowTable from a JSON string
mana_v2_udp_flow_table_instance = ManaV2UdpFlowTable.from_json(json)
# print the JSON string representation of the object
print(ManaV2UdpFlowTable.to_json())

# convert the object into a dict
mana_v2_udp_flow_table_dict = mana_v2_udp_flow_table_instance.to_dict()
# create an instance of ManaV2UdpFlowTable from a dict
mana_v2_udp_flow_table_from_dict = ManaV2UdpFlowTable.from_dict(mana_v2_udp_flow_table_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



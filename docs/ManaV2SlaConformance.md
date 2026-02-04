# ManaV2SlaConformance


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dampening_factor** | **int** |  | [optional] 
**duration** | **int** |  | [optional] 
**interval** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_sla_conformance import ManaV2SlaConformance

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SlaConformance from a JSON string
mana_v2_sla_conformance_instance = ManaV2SlaConformance.from_json(json)
# print the JSON string representation of the object
print(ManaV2SlaConformance.to_json())

# convert the object into a dict
mana_v2_sla_conformance_dict = mana_v2_sla_conformance_instance.to_dict()
# create an instance of ManaV2SlaConformance from a dict
mana_v2_sla_conformance_from_dict = ManaV2SlaConformance.from_dict(mana_v2_sla_conformance_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



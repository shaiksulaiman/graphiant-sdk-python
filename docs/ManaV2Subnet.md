# ManaV2Subnet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cidr** | **str** |  | [optional] 
**id** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_subnet import ManaV2Subnet

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Subnet from a JSON string
mana_v2_subnet_instance = ManaV2Subnet.from_json(json)
# print the JSON string representation of the object
print(ManaV2Subnet.to_json())

# convert the object into a dict
mana_v2_subnet_dict = mana_v2_subnet_instance.to_dict()
# create an instance of ManaV2Subnet from a dict
mana_v2_subnet_from_dict = ManaV2Subnet.from_dict(mana_v2_subnet_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



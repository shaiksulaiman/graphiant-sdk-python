# ManaV2NullableDhcpipRangeList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ip_range** | [**List[ManaV2DhcpipRangeConfig]**](ManaV2DhcpipRangeConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_nullable_dhcpip_range_list import ManaV2NullableDhcpipRangeList

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NullableDhcpipRangeList from a JSON string
mana_v2_nullable_dhcpip_range_list_instance = ManaV2NullableDhcpipRangeList.from_json(json)
# print the JSON string representation of the object
print(ManaV2NullableDhcpipRangeList.to_json())

# convert the object into a dict
mana_v2_nullable_dhcpip_range_list_dict = mana_v2_nullable_dhcpip_range_list_instance.to_dict()
# create an instance of ManaV2NullableDhcpipRangeList from a dict
mana_v2_nullable_dhcpip_range_list_from_dict = ManaV2NullableDhcpipRangeList.from_dict(mana_v2_nullable_dhcpip_range_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



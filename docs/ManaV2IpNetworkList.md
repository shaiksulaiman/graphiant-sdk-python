# ManaV2IpNetworkList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**networks** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ip_network_list import ManaV2IpNetworkList

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IpNetworkList from a JSON string
mana_v2_ip_network_list_instance = ManaV2IpNetworkList.from_json(json)
# print the JSON string representation of the object
print(ManaV2IpNetworkList.to_json())

# convert the object into a dict
mana_v2_ip_network_list_dict = mana_v2_ip_network_list_instance.to_dict()
# create an instance of ManaV2IpNetworkList from a dict
mana_v2_ip_network_list_from_dict = ManaV2IpNetworkList.from_dict(mana_v2_ip_network_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



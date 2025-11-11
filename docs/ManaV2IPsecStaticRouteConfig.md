# ManaV2IPsecStaticRouteConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_prefix** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_i_psec_static_route_config import ManaV2IPsecStaticRouteConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2IPsecStaticRouteConfig from a JSON string
mana_v2_i_psec_static_route_config_instance = ManaV2IPsecStaticRouteConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2IPsecStaticRouteConfig.to_json())

# convert the object into a dict
mana_v2_i_psec_static_route_config_dict = mana_v2_i_psec_static_route_config_instance.to_dict()
# create an instance of ManaV2IPsecStaticRouteConfig from a dict
mana_v2_i_psec_static_route_config_from_dict = ManaV2IPsecStaticRouteConfig.from_dict(mana_v2_i_psec_static_route_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



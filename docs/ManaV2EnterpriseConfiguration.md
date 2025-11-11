# ManaV2EnterpriseConfiguration


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**encryption** | **str** |  | [optional] 
**use_encryption** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_enterprise_configuration import ManaV2EnterpriseConfiguration

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2EnterpriseConfiguration from a JSON string
mana_v2_enterprise_configuration_instance = ManaV2EnterpriseConfiguration.from_json(json)
# print the JSON string representation of the object
print(ManaV2EnterpriseConfiguration.to_json())

# convert the object into a dict
mana_v2_enterprise_configuration_dict = mana_v2_enterprise_configuration_instance.to_dict()
# create an instance of ManaV2EnterpriseConfiguration from a dict
mana_v2_enterprise_configuration_from_dict = ManaV2EnterpriseConfiguration.from_dict(mana_v2_enterprise_configuration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



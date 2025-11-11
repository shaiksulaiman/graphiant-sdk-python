# V1EnterpriseConfigurationPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**configuration** | [**ManaV2EnterpriseConfiguration**](ManaV2EnterpriseConfiguration.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_enterprise_configuration_put_request import V1EnterpriseConfigurationPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1EnterpriseConfigurationPutRequest from a JSON string
v1_enterprise_configuration_put_request_instance = V1EnterpriseConfigurationPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1EnterpriseConfigurationPutRequest.to_json())

# convert the object into a dict
v1_enterprise_configuration_put_request_dict = v1_enterprise_configuration_put_request_instance.to_dict()
# create an instance of V1EnterpriseConfigurationPutRequest from a dict
v1_enterprise_configuration_put_request_from_dict = V1EnterpriseConfigurationPutRequest.from_dict(v1_enterprise_configuration_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



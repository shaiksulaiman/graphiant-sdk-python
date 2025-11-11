# V2IntegrationGetallEnterpriseIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**integrations** | [**List[AlertserviceIntegration]**](AlertserviceIntegration.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_integration_getall_enterprise_id_get_response import V2IntegrationGetallEnterpriseIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2IntegrationGetallEnterpriseIdGetResponse from a JSON string
v2_integration_getall_enterprise_id_get_response_instance = V2IntegrationGetallEnterpriseIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2IntegrationGetallEnterpriseIdGetResponse.to_json())

# convert the object into a dict
v2_integration_getall_enterprise_id_get_response_dict = v2_integration_getall_enterprise_id_get_response_instance.to_dict()
# create an instance of V2IntegrationGetallEnterpriseIdGetResponse from a dict
v2_integration_getall_enterprise_id_get_response_from_dict = V2IntegrationGetallEnterpriseIdGetResponse.from_dict(v2_integration_getall_enterprise_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



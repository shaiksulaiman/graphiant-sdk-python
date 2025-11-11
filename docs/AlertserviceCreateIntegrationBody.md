# AlertserviceCreateIntegrationBody


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_by** | **str** | ID of the user who created the integration | [optional] 
**created_on** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**details** | [**AlertserviceIntegrationDetails**](AlertserviceIntegrationDetails.md) |  | [optional] 
**enterprise** | **int** | ID of the enterprise (required) | 
**integration_type** | **str** | Type of integration (required) | 
**is_active** | **bool** | Indicates whether the integration is active | [optional] 
**nick_name** | **str** | Name of the integration (required) | 

## Example

```python
from graphiant_sdk.models.alertservice_create_integration_body import AlertserviceCreateIntegrationBody

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceCreateIntegrationBody from a JSON string
alertservice_create_integration_body_instance = AlertserviceCreateIntegrationBody.from_json(json)
# print the JSON string representation of the object
print(AlertserviceCreateIntegrationBody.to_json())

# convert the object into a dict
alertservice_create_integration_body_dict = alertservice_create_integration_body_instance.to_dict()
# create an instance of AlertserviceCreateIntegrationBody from a dict
alertservice_create_integration_body_from_dict = AlertserviceCreateIntegrationBody.from_dict(alertservice_create_integration_body_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



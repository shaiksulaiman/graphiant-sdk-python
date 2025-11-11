# AlertserviceUpdateIntegrationBody


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**details** | [**AlertserviceIntegrationDetails**](AlertserviceIntegrationDetails.md) |  | [optional] 
**enterprise** | **int** | ID of the enterprise (required) | 
**integration_type** | **str** | Type of integration (required) | 
**is_active** | **bool** | Indicates whether the integration is active | [optional] 
**nick_name** | **str** | nick name of the integration (required) | 
**updated_by** | **str** | ID of the user who updated the integration | [optional] 

## Example

```python
from graphiant_sdk.models.alertservice_update_integration_body import AlertserviceUpdateIntegrationBody

# TODO update the JSON string below
json = "{}"
# create an instance of AlertserviceUpdateIntegrationBody from a JSON string
alertservice_update_integration_body_instance = AlertserviceUpdateIntegrationBody.from_json(json)
# print the JSON string representation of the object
print(AlertserviceUpdateIntegrationBody.to_json())

# convert the object into a dict
alertservice_update_integration_body_dict = alertservice_update_integration_body_instance.to_dict()
# create an instance of AlertserviceUpdateIntegrationBody from a dict
alertservice_update_integration_body_from_dict = AlertserviceUpdateIntegrationBody.from_dict(alertservice_update_integration_body_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



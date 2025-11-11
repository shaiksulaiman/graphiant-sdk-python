# AssuranceExchangeServiceIdentifier


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**exchange_service_id** | **int** |  | [optional] 
**exchange_service_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_exchange_service_identifier import AssuranceExchangeServiceIdentifier

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceExchangeServiceIdentifier from a JSON string
assurance_exchange_service_identifier_instance = AssuranceExchangeServiceIdentifier.from_json(json)
# print the JSON string representation of the object
print(AssuranceExchangeServiceIdentifier.to_json())

# convert the object into a dict
assurance_exchange_service_identifier_dict = assurance_exchange_service_identifier_instance.to_dict()
# create an instance of AssuranceExchangeServiceIdentifier from a dict
assurance_exchange_service_identifier_from_dict = AssuranceExchangeServiceIdentifier.from_dict(assurance_exchange_service_identifier_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



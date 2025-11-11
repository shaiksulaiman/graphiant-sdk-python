# AssuranceTrendValue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**end_time** | **int** |  | [optional] 
**flow_count** | **int** |  | [optional] 
**start_time** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_trend_value import AssuranceTrendValue

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceTrendValue from a JSON string
assurance_trend_value_instance = AssuranceTrendValue.from_json(json)
# print the JSON string representation of the object
print(AssuranceTrendValue.to_json())

# convert the object into a dict
assurance_trend_value_dict = assurance_trend_value_instance.to_dict()
# create an instance of AssuranceTrendValue from a dict
assurance_trend_value_from_dict = AssuranceTrendValue.from_dict(assurance_trend_value_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



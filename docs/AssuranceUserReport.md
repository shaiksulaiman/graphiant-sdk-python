# AssuranceUserReport


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_by** | **List[str]** |  | [optional] 
**created_on** | **int** |  | [optional] 
**email_list** | **List[str]** |  | [optional] 
**enterprise_id** | **str** |  | [optional] 
**report_id** | **int** |  | [optional] 
**report_name** | **str** |  | [optional] 
**report_type** | **str** |  | [optional] 
**time_period** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.assurance_user_report import AssuranceUserReport

# TODO update the JSON string below
json = "{}"
# create an instance of AssuranceUserReport from a JSON string
assurance_user_report_instance = AssuranceUserReport.from_json(json)
# print the JSON string representation of the object
print(AssuranceUserReport.to_json())

# convert the object into a dict
assurance_user_report_dict = assurance_user_report_instance.to_dict()
# create an instance of AssuranceUserReport from a dict
assurance_user_report_from_dict = AssuranceUserReport.from_dict(assurance_user_report_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V2AssuranceReadUserReportListGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_report_list** | [**List[AssuranceUserReport]**](AssuranceUserReport.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_read_user_report_list_get_response import V2AssuranceReadUserReportListGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceReadUserReportListGetResponse from a JSON string
v2_assurance_read_user_report_list_get_response_instance = V2AssuranceReadUserReportListGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceReadUserReportListGetResponse.to_json())

# convert the object into a dict
v2_assurance_read_user_report_list_get_response_dict = v2_assurance_read_user_report_list_get_response_instance.to_dict()
# create an instance of V2AssuranceReadUserReportListGetResponse from a dict
v2_assurance_read_user_report_list_get_response_from_dict = V2AssuranceReadUserReportListGetResponse.from_dict(v2_assurance_read_user_report_list_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V2AllowlistByEnterpriseGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**records** | [**List[AlertserviceAllowAlertNotifcationListRecord]**](AlertserviceAllowAlertNotifcationListRecord.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_allowlist_by_enterprise_get_response import V2AllowlistByEnterpriseGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AllowlistByEnterpriseGetResponse from a JSON string
v2_allowlist_by_enterprise_get_response_instance = V2AllowlistByEnterpriseGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2AllowlistByEnterpriseGetResponse.to_json())

# convert the object into a dict
v2_allowlist_by_enterprise_get_response_dict = v2_allowlist_by_enterprise_get_response_instance.to_dict()
# create an instance of V2AllowlistByEnterpriseGetResponse from a dict
v2_allowlist_by_enterprise_get_response_from_dict = V2AllowlistByEnterpriseGetResponse.from_dict(v2_allowlist_by_enterprise_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



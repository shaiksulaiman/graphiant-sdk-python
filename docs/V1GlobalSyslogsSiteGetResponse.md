# V1GlobalSyslogsSiteGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**collectors** | [**List[ManaV2SyslogCollector]**](ManaV2SyslogCollector.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_syslogs_site_get_response import V1GlobalSyslogsSiteGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSyslogsSiteGetResponse from a JSON string
v1_global_syslogs_site_get_response_instance = V1GlobalSyslogsSiteGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSyslogsSiteGetResponse.to_json())

# convert the object into a dict
v1_global_syslogs_site_get_response_dict = v1_global_syslogs_site_get_response_instance.to_dict()
# create an instance of V1GlobalSyslogsSiteGetResponse from a dict
v1_global_syslogs_site_get_response_from_dict = V1GlobalSyslogsSiteGetResponse.from_dict(v1_global_syslogs_site_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



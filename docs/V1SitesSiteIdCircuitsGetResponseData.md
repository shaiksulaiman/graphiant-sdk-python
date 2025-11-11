# V1SitesSiteIdCircuitsGetResponseData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**circuits** | [**List[ManaV2Circuit]**](ManaV2Circuit.md) |  | [optional] 
**device_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_sites_site_id_circuits_get_response_data import V1SitesSiteIdCircuitsGetResponseData

# TODO update the JSON string below
json = "{}"
# create an instance of V1SitesSiteIdCircuitsGetResponseData from a JSON string
v1_sites_site_id_circuits_get_response_data_instance = V1SitesSiteIdCircuitsGetResponseData.from_json(json)
# print the JSON string representation of the object
print(V1SitesSiteIdCircuitsGetResponseData.to_json())

# convert the object into a dict
v1_sites_site_id_circuits_get_response_data_dict = v1_sites_site_id_circuits_get_response_data_instance.to_dict()
# create an instance of V1SitesSiteIdCircuitsGetResponseData from a dict
v1_sites_site_id_circuits_get_response_data_from_dict = V1SitesSiteIdCircuitsGetResponseData.from_dict(v1_sites_site_id_circuits_get_response_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1SitesSiteIdDevicesGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device** | [**List[ManaV2topologyDevice]**](ManaV2topologyDevice.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_sites_site_id_devices_get_response import V1SitesSiteIdDevicesGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1SitesSiteIdDevicesGetResponse from a JSON string
v1_sites_site_id_devices_get_response_instance = V1SitesSiteIdDevicesGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1SitesSiteIdDevicesGetResponse.to_json())

# convert the object into a dict
v1_sites_site_id_devices_get_response_dict = v1_sites_site_id_devices_get_response_instance.to_dict()
# create an instance of V1SitesSiteIdDevicesGetResponse from a dict
v1_sites_site_id_devices_get_response_from_dict = V1SitesSiteIdDevicesGetResponse.from_dict(v1_sites_site_id_devices_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



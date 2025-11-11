# V1EnterpriseSnapshotGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_snapshot_records** | [**List[ManaV2deviceSnapshotRow]**](ManaV2deviceSnapshotRow.md) |  | [optional] 
**device_snapshot_map** | [**Dict[str, ManaV2DeviceSnapshotList]**](ManaV2DeviceSnapshotList.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_enterprise_snapshot_get_response import V1EnterpriseSnapshotGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EnterpriseSnapshotGetResponse from a JSON string
v1_enterprise_snapshot_get_response_instance = V1EnterpriseSnapshotGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1EnterpriseSnapshotGetResponse.to_json())

# convert the object into a dict
v1_enterprise_snapshot_get_response_dict = v1_enterprise_snapshot_get_response_instance.to_dict()
# create an instance of V1EnterpriseSnapshotGetResponse from a dict
v1_enterprise_snapshot_get_response_from_dict = V1EnterpriseSnapshotGetResponse.from_dict(v1_enterprise_snapshot_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



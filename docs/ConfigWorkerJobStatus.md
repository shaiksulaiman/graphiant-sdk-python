# ConfigWorkerJobStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**completed_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**error** | **str** |  | [optional] 
**error_count** | **int** |  | [optional] 
**job_id** | **int** |  | [optional] 
**job_state** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.config_worker_job_status import ConfigWorkerJobStatus

# TODO update the JSON string below
json = "{}"
# create an instance of ConfigWorkerJobStatus from a JSON string
config_worker_job_status_instance = ConfigWorkerJobStatus.from_json(json)
# print the JSON string representation of the object
print(ConfigWorkerJobStatus.to_json())

# convert the object into a dict
config_worker_job_status_dict = config_worker_job_status_instance.to_dict()
# create an instance of ConfigWorkerJobStatus from a dict
config_worker_job_status_from_dict = ConfigWorkerJobStatus.from_dict(config_worker_job_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# V1DevicesDeviceIdJobsJobIdGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_id** | **int** |  | [optional] 
**job_status** | [**ConfigWorkerJobStatus**](ConfigWorkerJobStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_devices_device_id_jobs_job_id_get_response import V1DevicesDeviceIdJobsJobIdGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1DevicesDeviceIdJobsJobIdGetResponse from a JSON string
v1_devices_device_id_jobs_job_id_get_response_instance = V1DevicesDeviceIdJobsJobIdGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1DevicesDeviceIdJobsJobIdGetResponse.to_json())

# convert the object into a dict
v1_devices_device_id_jobs_job_id_get_response_dict = v1_devices_device_id_jobs_job_id_get_response_instance.to_dict()
# create an instance of V1DevicesDeviceIdJobsJobIdGetResponse from a dict
v1_devices_device_id_jobs_job_id_get_response_from_dict = V1DevicesDeviceIdJobsJobIdGetResponse.from_dict(v1_devices_device_id_jobs_job_id_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



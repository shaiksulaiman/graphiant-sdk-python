# V2AssuranceBucketServicesPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**services** | [**List[AssuranceExchangeServiceIdentifier]**](AssuranceExchangeServiceIdentifier.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_assurance_bucket_services_post_response import V2AssuranceBucketServicesPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2AssuranceBucketServicesPostResponse from a JSON string
v2_assurance_bucket_services_post_response_instance = V2AssuranceBucketServicesPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2AssuranceBucketServicesPostResponse.to_json())

# convert the object into a dict
v2_assurance_bucket_services_post_response_dict = v2_assurance_bucket_services_post_response_instance.to_dict()
# create an instance of V2AssuranceBucketServicesPostResponse from a dict
v2_assurance_bucket_services_post_response_from_dict = V2AssuranceBucketServicesPostResponse.from_dict(v2_assurance_bucket_services_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



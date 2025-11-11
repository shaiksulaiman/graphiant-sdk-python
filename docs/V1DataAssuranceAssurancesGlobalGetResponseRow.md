# V1DataAssuranceAssurancesGlobalGetResponseRow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apps** | [**List[V1DataAssuranceAssurancesGlobalGetResponseRowAppEntry]**](V1DataAssuranceAssurancesGlobalGetResponseRowAppEntry.md) |  | [optional] 
**assurance_id** | **int** |  | [optional] 
**assurance_name** | **str** |  | [optional] 
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**flex_algo** | **str** |  | [optional] 
**lans** | [**List[V1DataAssuranceAssurancesGlobalGetResponseRowLanEntry]**](V1DataAssuranceAssurancesGlobalGetResponseRowLanEntry.md) |  | [optional] 
**sites** | [**List[V1DataAssuranceAssurancesGlobalGetResponseRowSiteEntry]**](V1DataAssuranceAssurancesGlobalGetResponseRowSiteEntry.md) |  | [optional] 
**updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_data_assurance_assurances_global_get_response_row import V1DataAssuranceAssurancesGlobalGetResponseRow

# TODO update the JSON string below
json = "{}"
# create an instance of V1DataAssuranceAssurancesGlobalGetResponseRow from a JSON string
v1_data_assurance_assurances_global_get_response_row_instance = V1DataAssuranceAssurancesGlobalGetResponseRow.from_json(json)
# print the JSON string representation of the object
print(V1DataAssuranceAssurancesGlobalGetResponseRow.to_json())

# convert the object into a dict
v1_data_assurance_assurances_global_get_response_row_dict = v1_data_assurance_assurances_global_get_response_row_instance.to_dict()
# create an instance of V1DataAssuranceAssurancesGlobalGetResponseRow from a dict
v1_data_assurance_assurances_global_get_response_row_from_dict = V1DataAssuranceAssurancesGlobalGetResponseRow.from_dict(v1_data_assurance_assurances_global_get_response_row_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



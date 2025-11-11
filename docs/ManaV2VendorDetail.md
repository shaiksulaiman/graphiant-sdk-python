# ManaV2VendorDetail


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**neighbor_count** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_vendor_detail import ManaV2VendorDetail

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2VendorDetail from a JSON string
mana_v2_vendor_detail_instance = ManaV2VendorDetail.from_json(json)
# print the JSON string representation of the object
print(ManaV2VendorDetail.to_json())

# convert the object into a dict
mana_v2_vendor_detail_dict = mana_v2_vendor_detail_instance.to_dict()
# create an instance of ManaV2VendorDetail from a dict
mana_v2_vendor_detail_from_dict = ManaV2VendorDetail.from_dict(mana_v2_vendor_detail_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



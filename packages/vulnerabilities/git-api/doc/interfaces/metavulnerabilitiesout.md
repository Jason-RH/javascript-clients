[@redhat-cloud-services/vulnerabilities-client](../README.md) › [Globals](../globals.md) › [MetaVulnerabilitiesOut](metavulnerabilitiesout.md)

# Interface: MetaVulnerabilitiesOut

**`export`** 

**`interface`** MetaVulnerabilitiesOut

## Hierarchy

* [Meta](meta.md)

  ↳ **MetaVulnerabilitiesOut**

## Index

### Properties

* [business_risk_id](metavulnerabilitiesout.md#business_risk_id)
* [cvss_from](metavulnerabilitiesout.md#cvss_from)
* [cvss_to](metavulnerabilitiesout.md#cvss_to)
* [data_format](metavulnerabilitiesout.md#data_format)
* [filter](metavulnerabilitiesout.md#filter)
* [impact](metavulnerabilitiesout.md#impact)
* [limit](metavulnerabilitiesout.md#limit)
* [offset](metavulnerabilitiesout.md#offset)
* [page](metavulnerabilitiesout.md#page)
* [page_size](metavulnerabilitiesout.md#page_size)
* [pages](metavulnerabilitiesout.md#pages)
* [public_from](metavulnerabilitiesout.md#public_from)
* [public_to](metavulnerabilitiesout.md#public_to)
* [rule_presence](metavulnerabilitiesout.md#rule_presence)
* [security_rule](metavulnerabilitiesout.md#security_rule)
* [show_all](metavulnerabilitiesout.md#show_all)
* [sort](metavulnerabilitiesout.md#sort)
* [system_count](metavulnerabilitiesout.md#optional-system_count)
* [total_items](metavulnerabilitiesout.md#total_items)

## Properties

###  business_risk_id

• **business_risk_id**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:997](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L997)*

Filter based on business risk IDs.

**`memberof`** MetaVulnerabilitiesOut

___

###  cvss_from

• **cvss_from**: *number | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1003](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1003)*

Filter based on cvss score, starting from the value. Use -1 to include also CVEs with N/A cvss score.

**`memberof`** MetaVulnerabilitiesOut

___

###  cvss_to

• **cvss_to**: *number | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1009](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1009)*

Filter based on cvss score, up to the value.

**`memberof`** MetaVulnerabilitiesOut

___

###  data_format

• **data_format**: *string*

*Inherited from [Meta](meta.md).[data_format](meta.md#data_format)*

*Defined in [packages/vulnerabilities/git-api/api.ts:760](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L760)*

Format of the output data, either JSON (default) or CSV.

**`memberof`** Meta

___

###  filter

• **filter**: *string | null*

*Inherited from [Meta](meta.md).[filter](meta.md#filter)*

*Defined in [packages/vulnerabilities/git-api/api.ts:712](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L712)*

Full text filter

**`memberof`** Meta

___

###  impact

• **impact**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1033](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1033)*

Filter based on impact IDs.

**`memberof`** MetaVulnerabilitiesOut

___

###  limit

• **limit**: *number*

*Inherited from [Meta](meta.md).[limit](meta.md#limit)*

*Defined in [packages/vulnerabilities/git-api/api.ts:718](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L718)*

Maximum number of paginated results.

**`memberof`** Meta

___

###  offset

• **offset**: *number*

*Inherited from [Meta](meta.md).[offset](meta.md#offset)*

*Defined in [packages/vulnerabilities/git-api/api.ts:724](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L724)*

First record of paginated response.

**`memberof`** Meta

___

###  page

• **page**: *number*

*Inherited from [Meta](meta.md).[page](meta.md#page)*

*Defined in [packages/vulnerabilities/git-api/api.ts:730](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L730)*

Page number of paginated response.

**`memberof`** Meta

___

###  page_size

• **page_size**: *number*

*Inherited from [Meta](meta.md).[page_size](meta.md#page_size)*

*Defined in [packages/vulnerabilities/git-api/api.ts:736](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L736)*

Number of records per page of paginated response.

**`memberof`** Meta

___

###  pages

• **pages**: *number*

*Inherited from [Meta](meta.md).[pages](meta.md#pages)*

*Defined in [packages/vulnerabilities/git-api/api.ts:742](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L742)*

Total number of pages of paginated response.

**`memberof`** Meta

___

###  public_from

• **public_from**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1021](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1021)*

Filter CVEs based on their published date, starting from the date.

**`memberof`** MetaVulnerabilitiesOut

___

###  public_to

• **public_to**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1027](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1027)*

Filter CVEs based on their published date, up to the date.

**`memberof`** MetaVulnerabilitiesOut

___

###  rule_presence

• **rule_presence**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1045](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1045)*

Filter based on presence of security rule

**`memberof`** MetaVulnerabilitiesOut

___

###  security_rule

• **security_rule**: *boolean | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1051](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1051)*

Filter based on presence of security rule - deprecated

**`memberof`** MetaVulnerabilitiesOut

___

###  show_all

• **show_all**: *boolean | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1015](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1015)*

Show all known vulnerabilities, regardless of number of affected systems.

**`memberof`** MetaVulnerabilitiesOut

___

###  sort

• **sort**: *string | null*

*Inherited from [Meta](meta.md).[sort](meta.md#sort)*

*Defined in [packages/vulnerabilities/git-api/api.ts:748](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L748)*

Sorting filter.

**`memberof`** Meta

___

### `Optional` system_count

• **system_count**? : *number*

*Defined in [packages/vulnerabilities/git-api/api.ts:1039](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1039)*

Total number of systems managed by vulnerability application.

**`memberof`** MetaVulnerabilitiesOut

___

###  total_items

• **total_items**: *number*

*Inherited from [Meta](meta.md).[total_items](meta.md#total_items)*

*Defined in [packages/vulnerabilities/git-api/api.ts:754](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L754)*

Total number of records.

**`memberof`** Meta

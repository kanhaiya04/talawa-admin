[talawa-admin](../README.md) / [Modules](../modules.md) / screens/OrganizationFunds/OrganizationFundsMocks

# Module: screens/OrganizationFunds/OrganizationFundsMocks

## Table of contents

### Variables

- [MOCKS](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks)
- [MOCKS\_ARCHIVED\_FUND](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_archived_fund)
- [MOCKS\_ERROR\_ARCHIVED\_FUND](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_error_archived_fund)
- [MOCKS\_ERROR\_CREATE\_FUND](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_error_create_fund)
- [MOCKS\_ERROR\_ORGANIZATIONS\_FUNDS](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_error_organizations_funds)
- [MOCKS\_ERROR\_REMOVE\_FUND](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_error_remove_fund)
- [MOCKS\_ERROR\_UNARCHIVED\_FUND](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_error_unarchived_fund)
- [MOCKS\_ERROR\_UPDATE\_FUND](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_error_update_fund)
- [MOCKS\_UNARCHIVED\_FUND](screens_OrganizationFunds_OrganizationFundsMocks.md#mocks_unarchived_fund)

## Variables

### MOCKS

• `Const` **MOCKS**: (\{ `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false; `isDefault?`: `undefined` = false; `name?`: `undefined` = 'ActionItemCategory 1 updated'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible?`: `undefined` = true \}  \} ; `result`: \{ `data`: \{ `createFund?`: `undefined` ; `organizations`: \{ `funds`: \{ `_id`: `string` = '1'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[] ; `removeFund?`: `undefined` ; `updateFund?`: `undefined`  \}  \}  \} \| \{ `request`: \{ `query`: `DocumentNode` = CREATE\_FUND\_MUTATION; `variables`: \{ `id?`: `undefined` = '123'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Test Fund'; `organizationId`: `undefined` = undefined; `refrenceNumber`: `string` = '1'; `taxDeductible`: `boolean` = true \}  \} ; `result`: \{ `data`: \{ `createFund`: \{ `_id`: `string` = '3' \} ; `organizations?`: `undefined` ; `removeFund?`: `undefined` ; `updateFund?`: `undefined`  \}  \}  \} \| \{ `request`: \{ `query`: `DocumentNode` = UPDATE\_FUND\_MUTATION; `variables`: \{ `id`: `string` = '1'; `isArchived?`: `undefined` = false; `isDefault?`: `undefined` = false; `name`: `string` = 'Fund 1Test Fund Updated'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible?`: `undefined` = true \}  \} ; `result`: \{ `data`: \{ `createFund?`: `undefined` ; `organizations?`: `undefined` ; `removeFund?`: `undefined` ; `updateFund`: \{ `_id`: `string` = '1' \}  \}  \}  \} \| \{ `request`: \{ `query`: `DocumentNode` = REMOVE\_FUND\_MUTATION; `variables`: \{ `id`: `string` = '1'; `isArchived?`: `undefined` = false; `isDefault?`: `undefined` = false; `name?`: `undefined` = 'ActionItemCategory 1 updated'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible?`: `undefined` = true \}  \} ; `result`: \{ `data`: \{ `createFund?`: `undefined` ; `organizations?`: `undefined` ; `removeFund`: \{ `_id`: `string` = '1' \} ; `updateFund?`: `undefined`  \}  \}  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:8](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L8)

___

### MOCKS\_ARCHIVED\_FUND

• `Const` **MOCKS\_ARCHIVED\_FUND**: (\{ `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false \}  \} ; `result`: \{ `data`: \{ `organizations`: \{ `funds`: \{ `_id`: `string` = '1'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[] ; `updateFund?`: `undefined`  \}  \}  \} \| \{ `request`: \{ `query`: `DocumentNode` = UPDATE\_FUND\_MUTATION; `variables`: \{ `id`: `string` = '1'; `isArchived`: `boolean` = true \}  \} ; `result`: \{ `data`: \{ `organizations?`: `undefined` ; `updateFund`: \{ `_id`: `string` = '1' \}  \}  \}  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:231](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L231)

___

### MOCKS\_ERROR\_ARCHIVED\_FUND

• `Const` **MOCKS\_ERROR\_ARCHIVED\_FUND**: (\{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false \}  \} ; `result`: \{ `data`: \{ `organizations`: \{ `funds`: \{ `_id`: `string` = '1'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[]  \}  \}  \} \| \{ `error`: `Error` ; `request`: \{ `query`: `DocumentNode` = UPDATE\_FUND\_MUTATION; `variables`: \{ `id`: `string` = '1'; `isArchived`: `boolean` = true \}  \} ; `result?`: `undefined`  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:285](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L285)

___

### MOCKS\_ERROR\_CREATE\_FUND

• `Const` **MOCKS\_ERROR\_CREATE\_FUND**: (\{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false; `isDefault?`: `undefined` = false; `name?`: `undefined` = 'ActionItemCategory 1 updated'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible?`: `undefined` = true \}  \} ; `result`: \{ `data`: \{ `organizations`: \{ `funds`: \{ `_id`: `string` = '1'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[]  \}  \}  \} \| \{ `error`: `Error` ; `request`: \{ `query`: `DocumentNode` = CREATE\_FUND\_MUTATION; `variables`: \{ `id?`: `undefined` = '123'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 3'; `organizationId`: `undefined` = undefined; `refrenceNumber`: `string` = '789'; `taxDeductible`: `boolean` = true \}  \} ; `result?`: `undefined`  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:108](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L108)

___

### MOCKS\_ERROR\_ORGANIZATIONS\_FUNDS

• `Const` **MOCKS\_ERROR\_ORGANIZATIONS\_FUNDS**: \{ `error`: `Error` ; `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `organizationId`: `string` = '1' \}  \}  \}[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:97](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L97)

___

### MOCKS\_ERROR\_REMOVE\_FUND

• `Const` **MOCKS\_ERROR\_REMOVE\_FUND**: (\{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false; `isDefault?`: `undefined` = false; `name?`: `undefined` = 'ActionItemCategory 1 updated'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible?`: `undefined` = true \}  \} ; `result`: \{ `data`: \{ `createFund?`: `undefined` ; `organizations`: \{ `funds`: \{ `_id`: `string` = '3'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[] ; `updateFund?`: `undefined`  \}  \}  \} \| \{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = CREATE\_FUND\_MUTATION; `variables`: \{ `id?`: `undefined` = '123'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 3'; `organizationId`: `undefined` = undefined; `refrenceNumber`: `string` = '789'; `taxDeductible`: `boolean` = true \}  \} ; `result`: \{ `data`: \{ `createFund`: \{ `_id`: `string` = '3' \} ; `organizations?`: `undefined` ; `updateFund?`: `undefined`  \}  \}  \} \| \{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = UPDATE\_FUND\_MUTATION; `variables`: \{ `id`: `undefined` = undefined; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible`: `boolean` = true \}  \} ; `result`: \{ `data`: \{ `createFund?`: `undefined` ; `organizations?`: `undefined` ; `updateFund`: \{ `_id`: `string` = '1' \}  \}  \}  \} \| \{ `error`: `Error` ; `request`: \{ `query`: `DocumentNode` = REMOVE\_FUND\_MUTATION; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false; `isDefault?`: `undefined` = false; `name?`: `undefined` = 'ActionItemCategory 1 updated'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible?`: `undefined` = true \}  \} ; `result?`: `undefined`  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:435](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L435)

___

### MOCKS\_ERROR\_UNARCHIVED\_FUND

• `Const` **MOCKS\_ERROR\_UNARCHIVED\_FUND**: (\{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false \}  \} ; `result`: \{ `data`: \{ `organizations`: \{ `funds`: \{ `_id`: `string` = '1'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = true; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[]  \}  \}  \} \| \{ `error`: `Error` ; `request`: \{ `query`: `DocumentNode` = UPDATE\_FUND\_MUTATION; `variables`: \{ `id`: `string` = '1'; `isArchived`: `boolean` = false \}  \} ; `result?`: `undefined`  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:387](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L387)

___

### MOCKS\_ERROR\_UPDATE\_FUND

• `Const` **MOCKS\_ERROR\_UPDATE\_FUND**: (\{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false; `isDefault?`: `undefined` = false; `name?`: `undefined` = 'ActionItemCategory 1 updated'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible?`: `undefined` = true \}  \} ; `result`: \{ `data`: \{ `createFund?`: `undefined` ; `organizations`: \{ `funds`: \{ `_id`: `string` = '1'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[]  \}  \}  \} \| \{ `error?`: `undefined` ; `request`: \{ `query`: `DocumentNode` = CREATE\_FUND\_MUTATION; `variables`: \{ `id?`: `undefined` = '123'; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 3'; `organizationId`: `undefined` = undefined; `refrenceNumber`: `string` = '789'; `taxDeductible`: `boolean` = true \}  \} ; `result`: \{ `data`: \{ `createFund`: \{ `_id`: `string` = '3' \} ; `organizations?`: `undefined`  \}  \}  \} \| \{ `error`: `Error` ; `request`: \{ `query`: `DocumentNode` = UPDATE\_FUND\_MUTATION; `variables`: \{ `id`: `undefined` = undefined; `isArchived`: `boolean` = false; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `organizationId?`: `undefined` = '123'; `refrenceNumber?`: `undefined` = '1'; `taxDeductible`: `boolean` = true \}  \} ; `result?`: `undefined`  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:160](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L160)

___

### MOCKS\_UNARCHIVED\_FUND

• `Const` **MOCKS\_UNARCHIVED\_FUND**: (\{ `request`: \{ `query`: `DocumentNode` = ORGANIZATION\_FUNDS; `variables`: \{ `id`: `undefined` = undefined; `isArchived?`: `undefined` = false \}  \} ; `result`: \{ `data`: \{ `organizations`: \{ `funds`: \{ `_id`: `string` = '1'; `createdAt`: `string` = '2021-07-01T00:00:00.000Z'; `isArchived`: `boolean` = true; `isDefault`: `boolean` = false; `name`: `string` = 'Fund 1'; `refrenceNumber`: `string` = '123'; `taxDeductible`: `boolean` = true \}[]  \}[] ; `updateFund?`: `undefined`  \}  \}  \} \| \{ `request`: \{ `query`: `DocumentNode` = UPDATE\_FUND\_MUTATION; `variables`: \{ `id`: `string` = '1'; `isArchived`: `boolean` = false \}  \} ; `result`: \{ `data`: \{ `organizations?`: `undefined` ; `updateFund`: \{ `_id`: `string` = '1' \}  \}  \}  \})[]

#### Defined in

[src/screens/OrganizationFunds/OrganizationFundsMocks.tsx:333](https://github.com/kanhaiya04/talawa-admin/blob/52fefa1/src/screens/OrganizationFunds/OrganizationFundsMocks.tsx#L333)

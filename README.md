# Dataverse testdata

Dataverse testdata are a set of public testdata related for Dataverse.
It should collect and share testdata for the testing of Dataverse and external tools which use Dataverse data structures.

Testdata has been tested on a Dataverse 4.18.1 installation with pyDataverse 0.3.1.

Applications:

* [pyDataverse](https://github.com/gdcc/pyDataverse)
* [AUSSDA tests](https://github.com/AUSSDA/aussda_tests)

## TESTDATA

### JSON

#### Dataverse Collections

`dataverse_upload_min_01.json`

* Data type: Dataverse collection metadata
* Schema: Dataverse Upload Default
* Description: Minimum

`dataverse_upload_full_01.json`

* Data type: Dataverse collection metadata
* Schema: Dataverse Upload Default
* Description: Full

#### Datasets

**dataset_upload_default_min_01.json**

* Data type: Dataset metadata
* Schema: Dataverse Upload Default
* Description: Minimum

**dataset_upload_default_full_01.json**

* Data type: Dataset metadata
* Schema: Dataverse Upload Default
* Description: Full

#### Datafiles

**datafile_upload_full_01.json**

* Data type: Datafile metadata
* Schema: Dataverse Upload Default
* Description: Full

**datafile_upload_min_01.json**

* Data type: Datafile metadata
* Schema: Dataverse Upload Default
* Description: min

#### User

**user_01.json**

* Data type: User
* Schema: Dataverse Upload Default
* Description: 

## CONTRIBUTING

### Key-value naming

Align metadata naming to `json/dataset/dataset_upload_default_full_01.json`.

### File naming

**Dataverse**

dataverse_DIRECTION_FORMAT_NN.json

`dataverse_upload_full_01.json`

**Datasets**

dataset_DIRECTION_SCHEMA_FORMAT_NN.json

`dataset_upload_default_full_01.json`

**Datafiles**

datafile_DIRECTION_FORMAT_NN.json

`datafile_upload_full_01.json`

**User**

user_NN.json

`user_01.json`

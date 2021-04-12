# Dataverse testdata

Dataverse testdata are a set of public testdata related for Dataverse.
It should collect and share testdata for the testing of Dataverse and external tools which use Dataverse data structures.

Testdata has been tested on a Dataverse 4.18.1 installation with pyDataverse 0.3.1.

Applications:

* [pyDataverse](https://github.com/gdcc/pyDataverse)
* [AUSSDA tests](https://github.com/AUSSDA/aussda_tests)

## Standards

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

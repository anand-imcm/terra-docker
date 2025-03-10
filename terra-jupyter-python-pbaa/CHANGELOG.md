## 1.1.1 - 2023-07-06

- Fix bug introduced in https://github.com/DataBiosphere/terra-docker/commit/4a5b4c9212aedcafa2f41fbeb2b161089341c578 

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.1.1`

## 1.1.0 - 2023-06-23

- Update python 3.7 to 3.10

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.1.0`

## 1.0.15 - 2023-03-13T17:26:34.179905Z

- Update `terra-jupyter-base` to `1.0.14`
  - Include `jupyter lab build` step

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.15`

## 1.0.14 - 2023-02-09T14:18:49.058004Z

- Update `terra-jupyter-base` to `1.0.12`
  - Add cloud.google.com gpg key.

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.14`

## 1.0.13 - 2022-06-23T10:58:12.961300Z

- Update `terra-jupyter-base` to `1.0.10`
  - Fix leo_url variable in workspace_cromwell.py script for AoU projects

## 1.0.12 - 2022-06-23T10:58:12.961300Z

- reverted, do not use

## 1.0.11 - 2022-06-09

- Switch to requirements.txt file

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.11`

## 1.0.10 - 2022-06-03T18:35:22.435328Z

- reverted, do not use

## 1.0.9 - 2022-05-20T18:06:39.493915Z

- Update `terra-jupyter-base` to `1.0.9`
  - Fix adding workspace_cromwell.py script to manage Cromwell App

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.9`

## 1.0.8 - 2022-05-17T17:14:41.284361Z

- Update `terra-jupyter-base` to `1.0.8`
  - Add script that manages Cromwell app

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.8`

## 1.0.7 - 2022-05-10T22:08:25.979318Z

- Update `terra-jupyter-base` to `1.0.7`
  - Install Cromshell 2.0 (https://github.com/broadinstitute/cromshell)

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.7`

## 1.0.6 - 2022-05-02T14:33:23.968430Z

- Update `terra-jupyter-base` to `1.0.6`
  - use new nvidia key

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.6`

## 1.0.5 - 2022-04-17

- Update `terra-jupyter-base` to `1.0.5`
  - Install gcloud alpha storage dependency

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.5`

## 1.0.4 - 2022-02-02T20:47:42.360741Z

- Update `terra-jupyter-base` to `1.0.4`
  - update notebook_dir to $HOME; install scikit-learn-intelex, xgboost

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.4`

## 1.0.3 - 2022-01-06T18:21:41.192855Z

- Update `terra-jupyter-base` to `1.0.3`
  - Bumping Google Deeplearning image to 2.7, removing gcc-6 install due to package problems

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.3`

## 1.0.2 - 2021-10-07T14:47:43.398118Z

- Update `terra-jupyter-base` to `1.0.2`
  - Update AsyncMappingKernelManager https://github.com/jupyter/notebook/issues/6164

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.2`

## 1.0.1 - 2021-09-10T15:10:44.113546Z

- Update `terra-jupyter-base` to `1.0.1`
  - Update base image to gcr.io/deeplearning-platform-release/tf2-gpu.2-6 to support TensorFlow 2.6.0
  - Fix multipart Jupyter uploads

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.1`

## 1.0.0 - 2021-06-09T16:18:53.809656Z

- Update `terra-jupyter-base` to `1.0.0`
  - use `gcr.io/deeplearning-platform-release/base-cu110:latest` as base

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.0.0`

## 0.1.2 - 2021-05-05T16:19:57.509127Z

- Update `terra-jupyter-base` to `0.0.20`
  - [IA-1644] Install crcmod in base image to support GCS composite objects

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.1.2`

## 0.1.1 - 2021-04-5

- Add bug fix back in for python package ggplot (see https://github.com/yhat/ggpy/issues/662)

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.1.1`

## 0.1.0 - 2021-03-20

- Update all Python package versions by unpinning them.
- Add package `plotnine`. Fixes https://github.com/DataBiosphere/terra-docker/issues/126
- Replace package `tensorflow` with `tensorflow_cpu` to get rid of the warnings about GPUs being unavailable for Terra Cloud Runtimes.
- Add package `google-resumable-media` as an explicit dependency to ensure a more recent version of it is used. `pandas-gbq` depends on it for table uploads.
- Work around lack of 'bigquery.readsessions.create' permission [CA-1179] by uninstalling the dependency `google-cloud-bigquery-storage` so that flag `--use_rest_api` can be used with `%%bigquery` to use the older mechanism for data transfer.

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.1.0`

## 0.0.23 - 2021-01-20T16:00:48.318Z

- Update `terra-jupyter-base` to `0.0.19`
  - [IA-2472] Turn on debug-level logging when JUPYTER_DEBUG_LOGGING env var is true

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.23`

## 0.0.22 - 2020-12-09T18:50:57.262Z

- [IA-2420] Update to a newer version of pymc3

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.22`

## 0.0.21 - 2020-12-02T17:59:36.411Z

- Update `terra-jupyter-base` to `0.0.18`
  - bump terra-notebook-utils version to 0.7.0 and move it to base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.21`

## 0.0.20 - 2020-11-16T18:11:40.785376Z

- Update `terra-jupyter-base` to `0.0.17`
  - remove miniconda

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.20`

## 0.0.19 - 2020-11-10T13:26:19.077Z

- Remove Python package enum34. Fixes https://github.com/DataBiosphere/terra-docker/issues/175

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.19`

## 0.0.18 - 2020-10-26T20:13:57.706Z

- Update `terra-jupyter-base` to `0.0.16`
  - add keychain to base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.18`

## 0.0.17 - 2020-10-08T18:42:19.709Z

- Update `terra-jupyter-base` to `0.0.15`
  - include pip binary installation location in PATH

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.17`

## 0.0.16 - 2020-09-02T15:12:19.878Z

- Update `terra-jupyter-base` to `0.0.14`
  - Terminal now opens to /notebooks directory where PD is mounted

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.16`

## 0.0.15 - 2020-08-18T13:43:26.223Z

- Update `terra-jupyter-base` to `0.0.13`
  - update notebook to 6.1.1, tornado to 5.1.1

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.15`

## 0.0.14 - 07/27/2020

- Update `terra-jupyter-base` image version to `0.0.12`

Image URL `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.14`

## 0.0.13 - 06/15/2020

- Update `terra-jupyter-base` image version to `0.0.11`
- Add terra-notebook-utils package

Image URL `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.13`

## 0.0.12 - 05/18/2020

- Update `terra-jupyter-base` image version to `0.0.10`
   - Adds jupyter notebook extension collapsible headers and code-folding

Image URL `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.12`

## 0.0.11 - 04/17/2020

- Add Google Cloud support to pysam.
   
Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.11`

## 0.0.10 - 02/25/2020

- Update `terra-jupyter-base` version to `0.0.9`
   - Fixes https://broadworkbench.atlassian.net/browse/IA-1676
   
Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.10`

## 0.0.9 - 02/05/2020

- Update `terra-jupyter-base` version to `0.0.8`
   - Fixes https://broadworkbench.atlassian.net/browse/IA-1653

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.9`

## 0.0.8 - 01/17/2020

- Update `terra-jupyter-base` version to `0.0.7`
- Make docker image locally runnable with:
   - `docker run --rm -it -p 8000:8000 <image>`
- Remove FISS from this image since it's now included in the base
- Add OpenJDK 11

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.8`

## 0.0.7 - 01/15/2020

- Install `pandas-profiling` version `2.4.0`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.7`

## 0.0.6 - 12/12/2019

- Upgrade pandas from 0.23.4 to 0.25.3
- Upgrade pandas-gbq from 0.11.0 to 0.12.0
- Upgrade `google-cloud-bigquery` to `1.23.1`
- Upgrade `google-cloud-bigquery-datatransfer` to `0.4.1`
- Upgrade `google-cloud-datastore` to `1.10.0`
- Upgrade `google-cloud-resource-manager` to `0.30.0`
- Upgrade `google-cloud-storage` to `1.23.0`
- Upgrade `firecloud` to `0.16.25`
- Upgrade `six` to `1.13.0`
- Upgrade `setuptools` to `42.0.2`
- Install `pdoc3` instead of `pdoc`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.6`

## 0.0.5 - 11/26/2019

- Fix `WORKSPACE_BUCKET` environment variable

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.5`

## 0.0.4 - 11/16/2019

- Update `terra-jupyter-base` version to `0.0.5`
- Removed apt-get upgrade for security purposes

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.4`

## 0.0.3 - 10/18/2019

- Update `terra-jupyter-base` version to `0.0.4`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.3`

## 0.0.2 - 10/10/2019

Use jupyter base image 0.0.3

## 0.0.1 - 08/28/2019

- added pandas-gqb
- removed jupyter, jupyter-lab, unzip as they are in they base image
- removed google-cloud-core, was already satisfied as a dependency from other packages

 Package | Former Version | Current Version |
---|---|---|
 google-api-core | 1.5.0 | 1.6.0 |
 keras | 2.2.0 | 2.1.6 |
 markdown | 2.6.9 | 2.4.1 |
 pysam | 0.13 | 0.15.1 |
 scipy | 1.0.0 | 1.2 |
 tensorflow | 1.9.0 | 2.0.0a0 |
 certifi |	2016.2.28 | 2017.4.17 |
 google-cloud-bigquery | 1.7.0 | 1.9.0 |

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:0.0.1`

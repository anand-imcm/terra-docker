## 2.3.1 - 2023-07-06

- Fix bug introduced in https://github.com/DataBiosphere/terra-docker/commit/4a5b4c9212aedcafa2f41fbeb2b161089341c578 

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.3.1`

## 2.3.0 - 2023-06-23

- Update python 3.7 to 3.10

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.3.0`

## 2.2.14 - 2023-06-09

- Actually install bedtools to accessible path

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.14`

## 2.2.13 - 2023-06-01T17:49:47.668283846Z

- Update `terra-jupyter-r` to `2.1.10`
  - Bioconductor 3.17 release with R 4.3

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.13`

## 2.2.12 - 2023-05-31T13:55:05

- Add bcftools
- Add bedtools

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.12`

## 2.2.11 - 2023-03-13T17:26:34.219509Z

- Update `terra-jupyter-base` to `1.0.14`
  - Include `jupyter lab build` step

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.11`

## 2.2.10 - 2023-02-09T14:18:49.138553Z

- Update `terra-jupyter-base` to `1.0.12`
  - Add cloud.google.com gpg key.

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.10`

## 2.2.9 - 2022-11-22T20:49:44.110597220Z

- Update `terra-jupyter-r` to `2.1.7`
  - Update Bioconductor for 3.16 release

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.9`

## 2.2.8 - 2022-07-27T13:32:19.939107Z

- Update `terra-jupyter-r` to `2.1.6`
  - Installs AnVIL and supporting packages.

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.8`

## 2.2.7 - 2022-06-23T10:58:12.961300Z

- Update `terra-jupyter-base` to `1.0.10`
  - Fix leo_url variable in workspace_cromwell.py script for AoU projects
  
## 2.2.6 - 2022-06-23T10:58:12.961300Z

- reverted, do not use

## 2.2.5 - 2022-06-09

- Improve Python package matching from -python image. No longer causes downstream
  issues on package uninstall.

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.5`

## 2.2.4 - 2022-06-03T18:35:22.539434Z

- reverted, do not use

## 2.2.3 - 2022-05-20T18:06:39.552362Z

- Update `terra-jupyter-base` to `1.0.9`
  - Fix adding workspace_cromwell.py script to manage Cromwell App

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.3`

## 2.2.2 - 2022-05-17T17:14:41.328568Z

- Update `terra-jupyter-base` to `1.0.8`
  - Add script that manages Cromwell app

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.2`

## 2.2.1 - 2022-05-10T22:08:26.027031Z

- Update `terra-jupyter-base` to `1.0.7`
  - Install Cromshell 2.0 (https://github.com/broadinstitute/cromshell)

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.1`

## 2.2.0 - 2022-05-02

- Update `terra-jupyter-r` to `2.1.0`
  - Update Bioconductor to 3.15.0 and R to 4.2.0

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.2.0`

## 2.1.0 - 2022-05-02T14:33:24.006107Z

- Update `terra-jupyter-base` to `1.0.6`
  - use new nvidia key
- Install Nextflow

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.1.0`

## 2.0.9 - 2022-04-17

- Update `terra-jupyter-base` to `1.0.5`
  - Install gcloud alpha storage dependency

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.9`

## 2.0.8 - 2022-02-02T20:47:42.389262Z

- Update `terra-jupyter-base` to `1.0.4`
  - update notebook_dir to $HOME; install scikit-learn-intelex, xgboost

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.8`

## 2.0.7 - 2022-01-06T18:21:41.225176Z

- Update `terra-jupyter-base` to `1.0.3`
  - Bumping Google Deeplearning image to 2.7, removing gcc-6 and gcc-8 install due to package problems

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.7`

## 2.0.6 - 2021-12-14T19:48:03.830678Z

- Update `terra-jupyter-r` to `2.0.3`
  - Update Terra Jupyter image to use latest Bioconductor 3.14

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.6`

## 2.0.5 - 2021-12-15T18:29:12.526374Z

- Upgrade gatk image to 4.2.4.0

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.5`

## 2.0.4 - 2021-10-07T14:47:43.431586Z

- Update `terra-jupyter-base` to `1.0.2`
  - Update AsyncMappingKernelManager https://github.com/jupyter/notebook/issues/6164
- Unpinning cwltool version and updating protobuf version to 3.18

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.4`

## 2.0.3 - 2021-09-23

- [SUP-465] Terra base gatk notebook image needs Python dependencies
  - Added GATK Python Package install
  - Apply Patch for CNNScoreVariant bug

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.3`

## 2.0.2 - 2021-09-10T15:10:44.143280Z

- Update `terra-jupyter-base` to `1.0.1`
  - Update base image to gcr.io/deeplearning-platform-release/tf2-gpu.2-6 to support TensorFlow 2.6.0
  - Fix multipart Jupyter uploads

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.2`

## 2.0.1 - 2021-07-12

- Upgrade `gatk` version to `4.2.0.0`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.1`

## 2.0.0 - 2021-06-09T16:18:53.850703Z

- Update `terra-jupyter-base` to `1.0.0`
  - use `gcr.io/deeplearning-platform-release/base-cu110:latest` as base

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:2.0.0`

## 1.1.3 - 2021-06-07T19:39:55.994874Z

- Update `terra-jupyter-r` to `1.0.16`
  - Update R to 4.1.0 and Bioconductor version to 3.13.

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.1.3`

## 1.1.2 - 2021-05-05T16:19:57.539858Z

- Update `terra-jupyter-base` to `0.0.20`
  - [IA-1644] Install crcmod in base image to support GCS composite objects

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.1.2`

## 1.1.1 - 2021-04-05T17:29:05.428Z

- Update `terra-jupyter-python` to `0.1.1`
  - fix ggplot import bug

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.1.1`

## 1.1.0 - 2021-03-20

- Update `terra-jupyter-python` to `0.1.0`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.1.0`

## 1.0.15 - 2021-02-10T00:36:57.172Z

- Update `terra-jupyter-r` to `1.0.13`
  - [IA-2511] Install Seurat R package in terra-jupyter-r image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.15`

## 1.0.14 - 2021-01-20T16:00:48.352Z

- Update `terra-jupyter-base` to `0.0.19`
  - [IA-2472] Turn on debug-level logging when JUPYTER_DEBUG_LOGGING env var is true

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.14`

## 1.0.13 - 2020-12-09T18:50:57.311Z

- Update `terra-jupyter-python` to `0.0.22`
  - [IA-2420] Update to a newer version of pymc3

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.13`

## 1.0.12 - 2020-12-02T17:59:36.443Z

- Update `terra-jupyter-base` to `0.0.18`
  - bump terra-notebook-utils version to 0.7.0 and move it to base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.12`

## 1.0.11 - 2020-11-16T18:11:40.830329Z

- Update `terra-jupyter-base` to `0.0.17`
  - remove miniconda

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.11`

## 1.0.10 - 2020-11-10T13:26:19.126Z

- Update `terra-jupyter-python` to `0.0.19`
  - Remove Python package enum34. Fixes https://github.com/DataBiosphere/terra-docker/issues/175

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.10`

## 1.0.9 - 2020-11-04T21:43:54.895Z

- Update `terra-jupyter-r` to `1.0.9`
  - Version upgrades: Bioconductor version 3.12 and R version 4.0.3

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.9`

## 1.0.8 - 2020-10-26T20:13:57.750Z

- Update `terra-jupyter-base` to `0.0.16`
  - add keychain to base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.8`

## 1.0.7 - 2020-10-08T18:42:19.735Z

- Update `terra-jupyter-base` to `0.0.15`
  - include pip binary installation location in PATH

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.7`

## 1.0.6 - 2020-09-02T15:12:19.908Z

- Update `terra-jupyter-base` to `0.0.14`
  - Terminal now opens to /notebooks directory where PD is mounted

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.6`

## 1.0.5 - 2020-08-18T13:43:26.263Z

- Update `terra-jupyter-base` to `0.0.13`
  - update notebook to 6.1.1, tornado to 5.1.1

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.5`

## 1.0.4 - 07/27/2020

- Update `terra-jupyter-r` to `1.0.4`
- Update `terra-jupyter-python` to `0.0.14`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.4`

## 1.0.3 - 06/29/2020

- Only user package installations (not image package installations) will persist
- Update `terra-jupyter-r` version to `1.0.3`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.3`

## 1.0.2 - 06/26/2020

- Update `terra-jupyter-r` version to `1.0.2`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.2`

## 1.0.1 - 06/15/2020

- Update `terra-jupyter-python` base image to `0.0.32` and `terra-jupyter-r` base image to `1.0.1`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.1`

## 1.0.0 - 05/21/2020

- Update `terra-jupyter-r` base image to `1.0.0`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:1.0.0`

## 0.0.16 - 05/18/2020

- Update `terra-jupyter-python` base image to `0.0.12` and `terra-jupyter-r` base image to `0.0.14`
   - Adds jupyter notebook extension collapsible headers and code-folding

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.16`

## 0.0.15 - 04/28/2020

- Update `terra-jupyter-python` base image to `0.0.11`
   - Add Google Cloud support to pysam

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.15`

## 0.0.14 - 04/24/2020

- Update `terra-jupyter-r` version to `0.0.13`
- Update `terra-jupyter-gatk` version to `0.0.14`

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.14`

## 0.0.13 - 02/26/2020

- Install OpenJDK 8 instead of OpenJDK 11 to be compatible with GATK
   - Fixes https://broadworkbench.atlassian.net/browse/IA-1706

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.13`

## 0.0.12 - 02/25/2020

- Update `terra-jupyter-python` version to `0.0.10`
- Update `terra-jupyter-r` version to `0.0.11`
    - Fixes https://broadworkbench.atlassian.net/browse/IA-1676

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.12`                       

## 0.0.11 - 02/05/2020

- Update `terra-jupyter-python` version to `0.0.9`
- Update `terra-jupyter-r` version to `0.0.10`
- Fixes bug: https://broadworkbench.atlassian.net/browse/IA-1653

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.11`

## 0.0.10 - 01/17/2020

- Update `terra-jupyter-python` version to `0.0.8`
- Update `terra-jupyter-r` version to `0.0.9`
- Make docker image locally runnable with:
   - `docker run --rm -it -p 8000:8000 <image>`
- Remove `default-jre` and `default-jdk` since they are now provided in the base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.10`

## 0.0.9 - 1/15/2020

- Update `terra-jupyter-python` version to `0.0.7`
- Update `terra-jupyter-r` version to `0.0.8`

Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.9

## 0.0.8 - 1/11/2020

- Upgrade GATK version to `4.1.4.1`

Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.8

## 0.0.7 - 1/2/2020

- Upgrade `terra-jupyter-python` version

Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.7

## 0.0.6 - 11/26/2019

- Fix `WORKSPACE_BUCKET` environment variable

Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.6

## 0.0.5 - 11/22/2019
- Update `terra-jupyter-r` version to `0.0.6`

`Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.5`

## 0.0.4 - 11/16/2019
- Update `terra-jupyter-r` version to `0.0.5`
- Update `terra-jupyter-python` version to `0.0.4`
- Remove apt-get upgrade for security purposes

`Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.4`

## 0.0.3 - 10/18/2019
- Update `terra-jupyter-r` version to `0.0.4`

`Image URL: us.gcr.io/broad-dsp-gcr-public/terra-jupyter-gatk:0.0.3`

## 0.0.2 - 10/10/2019

Use version 0.0.2 of python image

## 0.0.1 - 09/24/2019

- added all from terra-jupyter-python:0.0.1
- added all from terra-jupyter-r:0.0.3
- added Open JDK
- added GATK 4.1.3.0
- added Samtools


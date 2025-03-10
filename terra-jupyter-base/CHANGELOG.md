## 1.1.1 - 2023-07-06

- Fix bug introduced in https://github.com/DataBiosphere/terra-docker/commit/4a5b4c9212aedcafa2f41fbeb2b161089341c578 

## 1.1.0 - 2023-06-23

- Upgrade python 3.7 to 3.10

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.1.0`
## 1.0.14 - 2023-03-13T17:26:34.128391Z

- Include `jupyter lab build` step

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.14`

## 1.0.13 - 2023-03-09

- Include `jupyter lab build` step

## 1.0.12 - 2023-02-09T14:18:48.948718Z

- Add cloud.google.com gpg key.

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.12`

## 1.0.11 - 2022-06-23T10:58:12.961300Z

- Fix leo_url variable in workspace_cromwell.py script for AoU projects

## 1.0.10 - 2022-06-03T18:35:22.582705Z

- reverted, do not use

## 1.0.9 - 2022-05-20T18:06:39.404395Z

- Fix adding workspace_cromwell.py script to manage Cromwell App

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.9`

## 1.0.8 - 2022-05-17T17:14:41.200567Z

- Add script that manages Cromwell app

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.8`

## 1.0.7 - 2022-05-10T22:08:25.901765Z

- Install Cromshell 2.0 (https://github.com/broadinstitute/cromshell)

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.7`

## 1.0.6 - 2022-05-02T14:33:23.893656Z

- use new nvidia key

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.6`

## 1.0.5 - 2022-04-17

- Install gcloud alpha storage dependency

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.5`

## 1.0.4 - 2022-02-02T20:47:42.308006Z

- update notebook_dir to $HOME

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.4`

## 1.0.3 - 2022-01-06T18:21:41.124056Z

- Bumping Google Deeplearning image to 2.7, removing gcc-6 and gcc-8 install due to package problems

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.3`

## 1.0.2 - 2021-10-07T14:47:43.325878Z

- Update AsyncMappingKernelManager https://github.com/jupyter/notebook/issues/6164

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.2`

## 1.0.1 - 2021-09-10T15:10:44.047182Z

- Update base image to gcr.io/deeplearning-platform-release/tf2-gpu.2-6 to support TensorFlow 2.6.0
- Fix multipart Jupyter uploads

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.1`

## 1.0.0 - 2021-06-09T16:18:53.734840Z

- use `gcr.io/deeplearning-platform-release/base-cu110:latest` as base

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:1.0.0`

## 0.0.20 - 2021-05-05T16:19:57.444846Z

- [IA-1644] Install crcmod in base image to support GCS composite objects

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.20`

## 0.0.19 - 2021-01-20T16:00:48.255Z

- [IA-2472] Turn on debug-level logging when JUPYTER_DEBUG_LOGGING env var is true

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.19`

## 0.0.18 - 2020-12-02T17:59:36.345Z

- bump terra-notebook-utils version to 0.7.0 and move it to base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.18`

## 0.0.17 - 2020-11-16T18:11:40.717364Z

- remove miniconda

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.17`

## 0.0.16 - 2020-10-26T20:13:57.592Z

- add keychain to base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.16`

## 0.0.15 - 2020-10-08T18:42:19.647Z

- include pip binary installation location in PATH

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.15`

## 0.0.14 - 2020-09-02T15:12:19.821Z

- Terminal now opens to /notebooks directory where PD is mounted

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.14`

## 0.0.13 - 2020-08-18T13:43:26.123Z

- update notebook to 6.1.1, tornado to 5.1.1

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.13`

## 0.0.12 - 07/27/2020
- Fix issue where packages with CLI functionality were not available on path

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.12`

## 0.0.11 - 06/15/2020
- Add terra-notebook-utils to base image
- Add /home/jupyter-user/notebooks/packages to PYTHONPATH so user package installs persist using PDs

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.11`

## 0.0.10 - 05/18/2020
- Adds jupyter notebook extension collapsible headers and code-folding

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.10`

## 0.0.9 - 02/25/2020
- Fixes https://broadworkbench.atlassian.net/browse/IA-1676 in `google_sign_in.js` 
    - Adds a fallback method to set needed config when in non-notebook views
- Lints .js files
- Fixes bug in `edit-mode.js` that caused errors in console due to modules loading prematurely
    - also renames saveAs function due to global namespace conflicts with https://github.com/eligrey/FileSaver.js
   
Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.9`

## 0.0.8 - 02/05/2020

- Fix bug in `google_sign_in.js` in the base image
   - See https://broadworkbench.atlassian.net/browse/IA-1653

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.8`

## 0.0.7 - 01/17/2020

- Make image locally runnable with:
   - `docker run --rm -it -p 8000:8000 <image>`
- Add FISS to base image
- Add OpenJDK 11 to base image

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.7`

## 0.0.6 - 11/26/2019

- Fix `WORKSPACE_BUCKET` environment variable

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.6`

## 0.0.5 - 11/16/2019

- Remove apt-get upgrade for security purposes

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.5`

## 0.0.4 - 10/18/2019

- Fix a bug in google_sign_in.js
- Fix WORKSPACE_NAME environment variable
  
Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.4`

## 0.0.3 - 10/09/2019

Check Metadata and lock interval on extension are now staggered

## 0.0.2 - 10/01/2019

Lint the .js extension files

## 0.0.1 - 08/21/2019

- Extends Ubuntu base image
- Add google-cloud-sdk
- Add Python 3.7
- Add pip
- Add conda
- Add Jupyter & JupyterLab
- Add Leonardo customizations/extensions

Image URL: `us.gcr.io/broad-dsp-gcr-public/terra-jupyter-base:0.0.1`

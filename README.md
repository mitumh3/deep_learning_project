# Download the data
## 1. Requirement
- Tool to download the data: `gdc-client` (https://gdc.cancer.gov/access-data/gdc-data-transfer-tool)
- Download file list: `gdc_manifest_72imgs.txt`

## 2. Execute download data using manifest file
```bash
gdc-client download -m  gdc_manifest_72imgs.txt
```
*Ref: https://docs.gdc.cancer.gov/Data_Transfer_Tool/Users_Guide/Data_Download_and_Upload/
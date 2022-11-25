### CARNet
## Zero-Shot Learning
- Download the AWA2 dataset using [link1](https://ucd87450812424dd5f5310084846.dl.dropboxusercontent.com/zip_download_get/BPxEKZxCv9OoR_JMA5jDhKlGlOLf6nXklQwUj2Fe6N45oaETF5UWcbWc_wkabae6xEtlJ6JIqfsF39A34c5w_qdIB4eeEMoX0b1IWKrDsHhi-Q?_download_id=9877838024212446752499356269108523061931480590683578519375119005&_notify_domain=www.dropbox.com)/[link2](https://www.dropbox.com/scl/fo/2a0lr4jjagfeok2cixsrv/h?dl=0&rlkey=0xn642sr9jsraacfnta1ti44d)
- Provide the path for the AWA2 dataset in the 'DATA_DIR' variable in the notebook 
- Run the **CARNet.ipynb** notebook to get the ZSL result of the proposed CARNet method for the AWA2 dataset 
- Variables 'USE_ATTRIBUTE_REFINEMENT' and 'USE_CIRCLE_LOSS' can be set to 'False' to get results without attribute refinement and circle loss 

## Continual Zero-Shot Learning
- Download the SUN dataset using [link1](https://uc5ffbbb53f9f9217615934f2b2f.dl.dropboxusercontent.com/zip_download_get/BQI5Zp1DQAqojOtijf36Lhg_MBdrrzpWpeDYLVBbCIew7TlhDZU75zD05UfQxKWvtlUUJPSipJ3mbXWPEWnQ8ex1CWG1qX8N5T99uzR6hjHSsQ?_download_id=5356830093390168981119861421958363831398700242488987834147786131&_notify_domain=www.dropbox.com)/[link2](https://www.dropbox.com/scl/fo/rnqfy39yunaiv04ducq99/h?dl=0&rlkey=eb7yqamjn03mlrux5udl9qrft)
- Provide the path for the SUN dataset in the 'DATA_DIR' variable in the notebook 
- Run the **CARNet_Continual_ZSL.ipynb** notebook to get the Continual ZSL result of the proposed CARNet method for the SUN dataset 

**Note**: Due to some unknown reasons, the code in the notebook might be repeated twice when viewed from the browser directly from the link. However, if you download the notebook and view it in the jupyter notebook this problem does not occur 

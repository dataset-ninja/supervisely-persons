Dataset **Supervisely Persons** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/I/r/L8/drYwelhvhHqdXwlQbZgUeDmy3IrckFk2O1YVsKOmJjQPEh36h4DBbwkwEkN3EJhVXrLt6v5bHfyymdNRWk1Bwb64o1bocOmLVRPXjxS13q2BkLVnH85fXCacOHly.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Supervisely Persons', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://cloud.enterprise.deepsystems.io/s/TK2z5TLYoAPl1w6/download).
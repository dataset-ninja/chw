Dataset **chw** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/p/V/0L/kvIDvvWEdUSVTaPqVOfZYNVLdjb4XoqIKXWhnFow4ytFGsZB4L3lopUyt5y6SJLBSlF3ZKNqS84f5mKQL7IvU7s4unAP8gROfTKW9RzySkkXhjShRvQN15yMxQHb.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='chw', dst_path='~/dtools/datasets/chw.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/jack-v5j2k/chw/dataset/3/download)
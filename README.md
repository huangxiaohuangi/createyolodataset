

代码运行说明:

python

```bash
python convert_to_voc.py #先将原始数据转为VOC格式的标注
python make_slice_voc.py #将上述图片切为小图，重新制作为voc.
python convert_voc_to_v5txt.py #将voc标注转换为yolov5的官方格式.
python make_yolov5_train_val.py #制作yolov5的train/val.
```

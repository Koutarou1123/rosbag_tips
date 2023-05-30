# rosbag_tips

## bag.activeを.bagに変換する方法

1.
```
rosbag reindex *.bag.active
```

2.origではないactiveファイルを選択
```
rosbag fix *.bag.active *.bag
```

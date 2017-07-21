# download dataset
  download dataset from [OTB ](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html/) 

# prepare dataset
## image sequence
```
    ffmpeg -i 1.mp4 -vsync vfr -qscale:v 2 ./img/%03d.jpg
```
## groundtruth_rect.txt
```
1101,142,178,200
1099,143,180,200
```

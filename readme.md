# Play gocv

`Require OpenCV V4.0`
`github gocv: https://github.com/hybridgroup/gocv`

## Prepare for run
```sh
brew install pkg-config
brew install glog
brew install hybridgroup/tools/opencv

## data for face detect example
mkdir data
curl -L "https://github.com/hybridgroup/gocv/blob/master/data/haarcascade_frontalface_default.xml?raw=true" > data/haarcascade_frontalface_default.xml
```
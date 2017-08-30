# Resources for Unboxing ML Models
From @rhdeck talk at Boston AI Meetup 8/29/2017

## Slides from my Boston AI Meetup Talk 
 - [PPT](RHD%20Boston%20AI%20Meetup%20%20082917.pptx)
 - [PDF](RHD%20Boston%20AI%20Meetup%20%20082917.pdf)
 - [Slideshare](https://www.slideshare.net/RayDeck1/unboxing-ml-models-plus-coreml)
## Useful Links
### HDF5 Viewers
 - Panoply; https://www.giss.nasa.gov/tools/panoply/ (Best for reading headers and getting charts from the stored data)
 - HDFView: https://support.hdfgroup.org/products/java/hdfview/index.html (Best for getting the raw numbers from the stored data)
### Protobuf Viewers
 - ProtobufViewer (MacOS): https://itunes.apple.com/us/app/protobuf-viewer/id1165908879?mt=12
 - Protobuf Editor (Windows): https://sourceforge.net/projects/protobufeditor/ (Requires .proto schema!)
### Protobuf Schemas
 - Caffe (V1): https://github.com/BVLC/caffe/blob/master/src/caffe/proto/caffe.proto
 - CNTK: https://github.com/Microsoft/CNTK/blob/master/Source/CNTKv2LibraryDll/proto/CNTK.proto
 - Tensorflow (Graphdef) https://github.com/tensorflow/tensorflow/blob/master/tensorflow/core/framework/graph.proto
### Prototxt Viewing
 - Netscope: https://ethereon.github.io/netscope Great for visualizing the graph in a caffe model. Can be ornery on the typing and style of the prototxt fed to it. Check out the presets!
### Zoos
 - Caffe: https://github.com/BVLC/caffe/wiki/Model-Zoo
 - CNTK: https://microsoft.com/en-us/cognitive-toolkit/features/model-gallery/
 - Tensorflow: https://github.com/tensorflow/models (deployed as python packages)
### CoreML Resources
 - Apple machine learning overview: https://developer.apple.com/machine-learning/
 - CoreML Proto specification: https://docs-assets.developer.apple.com/coreml/documentation/mlmodel_specification.zip
 - CoreML Tools: pip install coremltools
 - CoreML API: https://developer.apple.com/documentation/coreml/core_ml_api

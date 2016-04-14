GPU accelerated HEVC based on Inpainting algorithm

This is an HEVC Intra Prediction video codec implemented in Numpy packages and accelerated in PyOpenCL.

Linear solver part is accelerated based on lossless and lossy encoding methods. Other parts unfinished.

Another data transfer structure needed to be applied to this to overcome the bottleneck.

python run.py to run the encoding

python compare.py to see the performance difference

python toGrayscale.py to get the encoded image after encoding

While testing caffe models locally you may get following error 
```
if ms != self.inputs[in_][1:]:
    raise ValueError('Mean shape incompatible with input shape.')
```
To solve this problem, please replace following file
```
caffe_master/pyhton/caffe/io.py
```
By [This file](http://www.openu.ac.il/home/hassner/projects/cnn_agegender/io.py) 




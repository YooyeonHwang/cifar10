# cifar10
모델 설계해보기
++1. 필요한 모듈을 import해준다.++
<pre><code>
from __future__ import print_function
import keras
from keras.datasets import cifar10
from keras.preprocessing.image import ImageDataGenerator
from keras.models import Sequential
from keras.layers import Dense, Dropout, Activation, Flatten
from keras.layers import Conv2D, MaxPooling2D
from keras.layers import BatchNormalization

#warning 무시
import warnings
warnings.filterwarnings('ignore')

import os
</code></pre>

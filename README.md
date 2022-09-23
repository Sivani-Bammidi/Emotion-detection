# Emotion-detection
File path	pip command	reference url	version	To check wearther open cv installed
C:\Users\Sivani\emotion\Emotion-detection>pip install numpy	install numpy into phyton	https://numpy.org/install/	numpy-1.23.3	
c:\users\Sivani\appdata\roaming\python\python310\site-packages (from opencv-python) (1.23.3)	pip install opencv-python	https://www.geeksforgeeks.org/how-to-install-opencv-for-python-in-windows/	opencv-python-4.6.0.66	"C:\Users\Sivani>python
Python 3.10.7 (tags/v3.10.7:6cc6b13, Sep  5 2022, 14:08:36) [MSC v.1933 64 bit (AMD64)] on win32
Type ""help"", ""copyright"", ""credits"" or ""license"" for more information.
>>> import cv2
>>> print(cv2.__version__)
4.6.0
>>>"
"Microsoft Windows [Version 10.0.22000.978]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Sivani>pip install tensorflow
Defaulting to user installation because normal site-packages is not writeable
Collecting tensorflow
  Downloading tensorflow-2.10.0-cp310-cp310-win_amd64.whl (455.9 MB)
     ---------------------------------------- 455.9/455.9 MB 2.1 MB/s eta 0:00:00
Collecting termcolor>=1.1.0
  Downloading termcolor-2.0.1-py3-none-any.whl (5.4 kB)
Collecting tensorflow-io-gcs-filesystem>=0.23.1
  Downloading tensorflow_io_gcs_filesystem-0.27.0-cp310-cp310-win_amd64.whl (1.5 MB)
     ---------------------------------------- 1.5/1.5 MB 8.6 MB/s eta 0:00:00
Collecting keras-preprocessing>=1.1.1
  Downloading Keras_Preprocessing-1.1.2-py2.py3-none-any.whl (42 kB)
     ---------------------------------------- 42.6/42.6 kB 1.0 MB/s eta 0:00:00
Collecting astunparse>=1.6.0
  Downloading astunparse-1.6.3-py2.py3-none-any.whl (12 kB)
Requirement already satisfied: numpy>=1.20 in c:\users\Sivani\appdata\roaming\python\python310\site-packages (from tensorflow) (1.23.3)
Collecting grpcio<2.0,>=1.24.3
  Downloading grpcio-1.49.0-cp310-cp310-win_amd64.whl (3.6 MB)
     ---------------------------------------- 3.6/3.6 MB 8.0 MB/s eta 0:00:00
Collecting tensorflow-estimator<2.11,>=2.10.0
  Downloading tensorflow_estimator-2.10.0-py2.py3-none-any.whl (438 kB)
     ---------------------------------------- 438.7/438.7 kB 3.4 MB/s eta 0:00:00
Collecting gast<=0.4.0,>=0.2.1
  Downloading gast-0.4.0-py3-none-any.whl (9.8 kB)
Collecting wrapt>=1.11.0
  Downloading wrapt-1.14.1-cp310-cp310-win_amd64.whl (35 kB)
Collecting google-pasta>=0.1.1
  Downloading google_pasta-0.2.0-py3-none-any.whl (57 kB)
     ---------------------------------------- 57.5/57.5 kB 1.5 MB/s eta 0:00:00
Collecting h5py>=2.9.0
  Downloading h5py-3.7.0-cp310-cp310-win_amd64.whl (2.6 MB)
     ---------------------------------------- 2.6/2.6 MB 4.9 MB/s eta 0:00:00
Collecting libclang>=13.0.0
  Downloading libclang-14.0.6-py2.py3-none-win_amd64.whl (14.2 MB)
     ---------------------------------------- 14.2/14.2 MB 7.0 MB/s eta 0:00:00
Collecting six>=1.12.0
  Downloading six-1.16.0-py2.py3-none-any.whl (11 kB)
Collecting absl-py>=1.0.0
  Downloading absl_py-1.2.0-py3-none-any.whl (123 kB)
     ---------------------------------------- 123.4/123.4 kB 3.6 MB/s eta 0:00:00
Collecting tensorboard<2.11,>=2.10
  Downloading tensorboard-2.10.0-py3-none-any.whl (5.9 MB)
     ---------------------------------------- 5.9/5.9 MB 7.1 MB/s eta 0:00:00
Collecting protobuf<3.20,>=3.9.2
  Downloading protobuf-3.19.5-cp310-cp310-win_amd64.whl (895 kB)
     ---------------------------------------- 895.7/895.7 kB 5.7 MB/s eta 0:00:00
Collecting keras<2.11,>=2.10.0
  Downloading keras-2.10.0-py2.py3-none-any.whl (1.7 MB)
     ---------------------------------------- 1.7/1.7 MB 4.1 MB/s eta 0:00:00
Collecting typing-extensions>=3.6.6
  Downloading typing_extensions-4.3.0-py3-none-any.whl (25 kB)
Collecting flatbuffers>=2.0
  Downloading flatbuffers-2.0.7-py2.py3-none-any.whl (26 kB)
Collecting packaging
  Downloading packaging-21.3-py3-none-any.whl (40 kB)
     ---------------------------------------- 40.8/40.8 kB 649.1 kB/s eta 0:00:00
Collecting opt-einsum>=2.3.2
  Downloading opt_einsum-3.3.0-py3-none-any.whl (65 kB)
     ---------------------------------------- 65.5/65.5 kB 891.1 kB/s eta 0:00:00
Requirement already satisfied: setuptools in c:\program files\python310\lib\site-packages (from tensorflow) (63.2.0)
Collecting wheel<1.0,>=0.23.0
  Downloading wheel-0.37.1-py2.py3-none-any.whl (35 kB)
Collecting markdown>=2.6.8
  Downloading Markdown-3.4.1-py3-none-any.whl (93 kB)
     ---------------------------------------- 93.3/93.3 kB 1.3 MB/s eta 0:00:00
Collecting tensorboard-data-server<0.7.0,>=0.6.0
  Downloading tensorboard_data_server-0.6.1-py3-none-any.whl (2.4 kB)
Collecting google-auth<3,>=1.6.3
  Downloading google_auth-2.11.0-py2.py3-none-any.whl (167 kB)
     ---------------------------------------- 167.2/167.2 kB 3.3 MB/s eta 0:00:00
Collecting werkzeug>=1.0.1
  Downloading Werkzeug-2.2.2-py3-none-any.whl (232 kB)
     ---------------------------------------- 232.7/232.7 kB 2.4 MB/s eta 0:00:00
Collecting google-auth-oauthlib<0.5,>=0.4.1
  Downloading google_auth_oauthlib-0.4.6-py2.py3-none-any.whl (18 kB)
Collecting requests<3,>=2.21.0
  Downloading requests-2.28.1-py3-none-any.whl (62 kB)
     ---------------------------------------- 62.8/62.8 kB 3.5 MB/s eta 0:00:00
Collecting tensorboard-plugin-wit>=1.6.0
  Downloading tensorboard_plugin_wit-1.8.1-py3-none-any.whl (781 kB)
     ---------------------------------------- 781.3/781.3 kB 7.0 MB/s eta 0:00:00
Collecting pyparsing!=3.0.5,>=2.0.2
  Downloading pyparsing-3.0.9-py3-none-any.whl (98 kB)
     ---------------------------------------- 98.3/98.3 kB 1.9 MB/s eta 0:00:00
Collecting pyasn1-modules>=0.2.1
  Downloading pyasn1_modules-0.2.8-py2.py3-none-any.whl (155 kB)
     ---------------------------------------- 155.3/155.3 kB 9.7 MB/s eta 0:00:00
Collecting rsa<5,>=3.1.4
  Downloading rsa-4.9-py3-none-any.whl (34 kB)
Collecting cachetools<6.0,>=2.0.0
  Downloading cachetools-5.2.0-py3-none-any.whl (9.3 kB)
Collecting requests-oauthlib>=0.7.0
  Downloading requests_oauthlib-1.3.1-py2.py3-none-any.whl (23 kB)
Collecting idna<4,>=2.5
  Downloading idna-3.4-py3-none-any.whl (61 kB)
     ---------------------------------------- 61.5/61.5 kB 1.6 MB/s eta 0:00:00
Collecting certifi>=2017.4.17
  Downloading certifi-2022.9.14-py3-none-any.whl (162 kB)
     ---------------------------------------- 162.5/162.5 kB 3.2 MB/s eta 0:00:00
Collecting charset-normalizer<3,>=2
  Downloading charset_normalizer-2.1.1-py3-none-any.whl (39 kB)
Collecting urllib3<1.27,>=1.21.1
  Downloading urllib3-1.26.12-py2.py3-none-any.whl (140 kB)
     ---------------------------------------- 140.4/140.4 kB 2.8 MB/s eta 0:00:00
Collecting MarkupSafe>=2.1.1
  Downloading MarkupSafe-2.1.1-cp310-cp310-win_amd64.whl (17 kB)
Collecting pyasn1<0.5.0,>=0.4.6
  Downloading pyasn1-0.4.8-py2.py3-none-any.whl (77 kB)
     ---------------------------------------- 77.1/77.1 kB 1.4 MB/s eta 0:00:00
Collecting oauthlib>=3.0.0
  Downloading oauthlib-3.2.1-py3-none-any.whl (151 kB)
     ---------------------------------------- 151.7/151.7 kB 2.2 MB/s eta 0:00:00
Installing collected packages: tensorboard-plugin-wit, pyasn1, libclang, keras, flatbuffers, wrapt, wheel, urllib3, typing-extensions, termcolor, tensorflow-io-gcs-filesystem, tensorflow-estimator, tensorboard-data-server, six, rsa, pyparsing, pyasn1-modules, protobuf, opt-einsum, oauthlib, MarkupSafe, markdown, idna, h5py, gast, charset-normalizer, certifi, cachetools, absl-py, werkzeug, requests, packaging, keras-preprocessing, grpcio, google-pasta, google-auth, astunparse, requests-oauthlib, google-auth-oauthlib, tensorboard, tensorflow
  WARNING: The script wheel.exe is installed in 'C:\Users\Sivani\AppData\Roaming\Python\Python310\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts pyrsa-decrypt.exe, pyrsa-encrypt.exe, pyrsa-keygen.exe, pyrsa-priv2pub.exe, pyrsa-sign.exe and pyrsa-verify.exe are installed in 'C:\Users\Sivani\AppData\Roaming\Python\Python310\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script markdown_py.exe is installed in 'C:\Users\Sivani\AppData\Roaming\Python\Python310\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script normalizer.exe is installed in 'C:\Users\Sivani\AppData\Roaming\Python\Python310\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script google-oauthlib-tool.exe is installed in 'C:\Users\Sivani\AppData\Roaming\Python\Python310\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script tensorboard.exe is installed in 'C:\Users\Sivani\AppData\Roaming\Python\Python310\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The scripts estimator_ckpt_converter.exe, import_pb_to_tensorboard.exe, saved_model_cli.exe, tensorboard.exe, tf_upgrade_v2.exe, tflite_convert.exe, toco.exe and toco_from_protos.exe are installed in 'C:\Users\Sivani\AppData\Roaming\Python\Python310\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed MarkupSafe-2.1.1 absl-py-1.2.0 astunparse-1.6.3 cachetools-5.2.0 certifi-2022.9.14 charset-normalizer-2.1.1 flatbuffers-2.0.7 gast-0.4.0 google-auth-2.11.0 google-auth-oauthlib-0.4.6 google-pasta-0.2.0 grpcio-1.49.0 h5py-3.7.0 idna-3.4 keras-2.10.0 keras-preprocessing-1.1.2 libclang-14.0.6 markdown-3.4.1 oauthlib-3.2.1 opt-einsum-3.3.0 packaging-21.3 protobuf-3.19.5 pyasn1-0.4.8 pyasn1-modules-0.2.8 pyparsing-3.0.9 requests-2.28.1 requests-oauthlib-1.3.1 rsa-4.9 six-1.16.0 tensorboard-2.10.0 tensorboard-data-server-0.6.1 tensorboard-plugin-wit-1.8.1 tensorflow-2.10.0 tensorflow-estimator-2.10.0 tensorflow-io-gcs-filesystem-0.27.0 termcolor-2.0.1 typing-extensions-4.3.0 urllib3-1.26.12 werkzeug-2.2.2 wheel-0.37.1 wrapt-1.14.1"		pip install tensorflow		
"Name: tensorflow
Version: 2.10.0
Summary: TensorFlow is an open source machine learning framework for everyone.
Home-page: https://www.tensorflow.org/
Author: Google Inc.
Author-email: packages@tensorflow.org
License: Apache 2.0
Location: c:\users\Sivani\appdata\roaming\python\python310\site-packages
Requires: absl-py, astunparse, flatbuffers, gast, google-pasta, grpcio, h5py, keras, keras-preprocessing, libclang, numpy, opt-einsum, packaging, protobuf, setuptools, six, tensorboard, tensorflow-estimator, tensorflow-io-gcs-filesystem, termcolor, typing-extensions, wrapt
Required-by:"	pip show tensorflow	tensor flow version ML framework		
![image](https://user-images.githubusercontent.com/110295819/190874413-651dad53-874e-436e-95d4-8260af3584a9.png)


Required Software's to be installed

1.Python latest version
2.numpy
3.opencv-python
4.tensorflow
5.matplotlib

Program Execution steps
If you want to train this model, use:
cd src
python emotions.py --mode train
If you want to view the predictions without training again, you can download the pre-trained model from here and then run:
cd src
python emotions.py --mode display


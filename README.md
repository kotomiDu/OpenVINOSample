# OpenVINOSample
C++ based classification demo for openvino 2022.1 new api

>You can try OpenVINO™ 2022.1 pre-release version [here](https://github.com/openvinotoolkit/openvino/releases/tag/2022.1.0.dev20220215)

* This is a C++ project(VS 2019) to show how to use OpenVINO 2.0 as third-party. The command line is `OpenVINOSample.exe  ..\..\model\squeezenet1.1.xml ..\..\data\cat.jpg CPU`
* If you want to learn more samples, please check [OpenVINO published demo repo](https://github.com/openvinotoolkit/open_model_zoo/tree/master/demos)
* You can use the following command to get more tools in OpenVINO
  - OpenVINO™ Runtime for Python: `pip install openvino==2022.1.0` 
  - OpenVINO™ Development tools: `pip install openvino-dev==2022.1.0` 
    - use `mo  -h` to convert OpenVINO supported model
    - use `benchmark_app -h` to test performance


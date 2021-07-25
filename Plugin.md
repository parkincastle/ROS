# Plugin이란?
Gazebo 플로그인은 URDF 모델에 더 많은 기능을 제공하고 센서 출력 및 모터 입력에 대한 ROS 메시지 및 서비스 호출을 연결할 수 있다. 

## 플러그인 유형
1. Physical Model API에 대한 액세스를 제공하기 위한 ModelPlugins
2. Sensor API에 대한 액세스를 제공하기 위한 SensorPlugins
3. Rendering Visual API 에 대한 액세스를 제공하기 위한 VisualPlugins

## ModelPlugin을 추가하는 법
즉 ModelPlugin, `robot` 요소 내무의 URDF에 삽입된다.



# TETRA-DSV_M

##   Hyulimnetworks_company TETRA-DSV ROS Dev .. mwcha

************************

### 모든 tetra-DSV 는 M 모델을 기준으로 튜닝되었습니다.
### All tetra-DSV are tuned to the M model as a base.

************************
     
#### tetraDS : TETRA-DSV구동 보드와의 Serial통신을 통하여 Motor의 구동을 담당하는 패키지 (RS232통신 사용)
#### tetraDS : Package responsible for driving the motor through serial communication with the TETRA-DSV driving board (using RS232 communication)

#### tetraDS_description : TETRA-DSV의 URDF가 포함된 패키지 (gazebo 지원 X)
#### tetraDS_description : Package with URDF of TETRA-DSV (doesn`t support gazebo)

#### tetraDS_interface : TETRA-DSV의 전원공급, LED/GPIO 등의 제어를 제공하는 보드 사용 패키지 (RS232통신 사용)
#### tetraDS_interface: Board usage package that provides control of TETRA-DSV's power supply, LED / GPIO, etc. (using RS232 communication)

#### tetraDS_landmark : 인식되는 ar_tag를 이용하여 마커를 저장/표시하기 위한 패키지
#### tetraDS_landmark: Package for storing/displaying markers using recognized ar_tags

#### tetraDS_TCP : 외부 디바이스와 ROS 간의 다이렉트 Socket통신을 위하여 제작한 통신용 패키지
#### tetraDS_TCP: Communication package created for direct socket communication between external devices and ROS

#### tetraDS_service : TETRA-DSV의 환경지도/자율주행/각종 기능들에 서비스를 사용하기 위한 패키지
#### tetraDS_service: Package for using services for environmental map/autonomous driving/various functions of TETRA-DSV

#### tetraDS_2dnav : TETRA-DSV의 각종 설정 파일과 런치 파일들을 모아둔 패키지
#### tetraDS_2dnav: A package that collects various configuration files and launch files of TETRA-DSV

#### virtual_costmap_layer : GMahmoud가 만든 가상 레이어 패키지 (Global costmap에 활용)
#### virtual_costmap_layer: Virtual layer package created by GMahmoud (used for global costmap)

#### virtual_costmap_layer2 : GMahmoud가 만든 가상 레이어 패키지에서 플러그인 이름만 수정한 버전 (local costmap에 활용)
#### virtual_costmap_layer2: A version with only the plugin name modified from the virtual layer package created by GMahmoud (used for local costmap)

<br>

![1](https://user-images.githubusercontent.com/103166594/220823974-8fde85da-4c52-4bb3-9638-9e6d5bca1c39.png)

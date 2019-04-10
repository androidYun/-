## 医生端接口需要更改

### 一，绑定和解绑接口

  1,登录接口 api/user/login
  
  2，退出登录接口api/user/logout
  
  3，获取车辆是否绑定信息  api/user/getUserState
  
  4，绑定车辆接口 api/user/startWork
### 二，车辆接口

  1,车辆操作接口 驶向现场 到达医院 防空车 等等接口    api/vehicle/pauseVehicle
  
  2，获取车辆信息接口  api/vehicle/getVehicleState
  
  3，同步任务状态接口 可以增加一个 vehicleCode
  
  4,获取绑定设备列表 确实车辆绑定参数  api/v1/doctor/ecgGroup接口
  
  5,车辆 放空车和暂停调用字典接口  api/dict/getDefineData
  

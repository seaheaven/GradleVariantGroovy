基于Android Studio Koala Feature Drop | 2024.1.2版本创建的新项目
Gradle8.7 AGP 8.6.0 各版本配置参见[Android Studio Koala各种版本傻傻分不清]()

做了两项修改
- compileSdk改成35
  运行报错compileSdk默认是34，androidx.core:core:1.15.0、androidx.core:core-ktx:1.15.0最低支持35。
- .gitignore修改，直接看根目录下此文件

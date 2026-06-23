![image](https://user-images.githubusercontent.com/11009876/148997642-8a54899a-8547-44a8-a211-b7d8f4b9b063.png)

# 旋转大师
- 在浏览器中试用：https://iwatake2222.github.io/rotation_master/rotation_master.html
- 提供以下 3D 旋转表示方式之间的转换，并可视化刚体姿态
    - 旋转矩阵
    - 旋转向量
    - 轴角
    - 四元数
    - 欧拉角（内旋；移动）
    - 欧拉角（外旋；固定）

https://user-images.githubusercontent.com/11009876/148988739-5f775a11-c923-4557-aff7-12b9a4811d36.mp4

## CI/CD 状态
状态 | 详情
------ | ----------
[![CMake](https://github.com/iwatake2222/rotation_master/actions/workflows/cmake.yml/badge.svg)](https://github.com/iwatake2222/rotation_master/actions/workflows/cmake.yml) | ubuntu-20.04, windows-2019, macos-10.15
[![CodeQL](https://github.com/iwatake2222/rotation_master/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/iwatake2222/rotation_master/actions/workflows/codeql-analysis.yml) | ubuntu-20.04
[![WASM Deploy](https://github.com/iwatake2222/rotation_master/actions/workflows/release_emscripten.yml/badge.svg)](https://github.com/iwatake2222/rotation_master/actions/workflows/release_emscripten.yml) | https://iwatake2222.github.io/rotation_master/rotation_master.html

## 使用说明
https://github.com/iwatake2222/rotation_master/wiki/How-to-Use

## 构建说明
https://github.com/iwatake2222/rotation_master/wiki/How-to-Build

# 许可证
- 旋转大师
- 版权所有 2022 iwatake2222
- [根据 Apache License, Version 2.0 授权](LICENSE)

# 致谢
- [NOTICE.md](NOTICE.md)
- 本项目受 3D Rotation Converter 启发
    - https://www.andre-gaschler.com/rotationconverter/
- @astomih 使用 WASM + Emscripten 将本项目移植到浏览器，我参考了他/她的代码
    - https://github.com/astomih/rotation_master
- 我通过以下资料学习 OpenGL + GLFW，并在本项目中使用了部分示例代码
    - https://tokoik.github.io/GLFWdraft.pdf : GLFW による OpenGL 入門（PDF）

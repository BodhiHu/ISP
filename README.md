# ISP - Image Signal Processing

#### Pipeline

<img src="https://raw.githubusercontent.com/BodhiHu/xkISP/main/imgs/pipeline.png" />

#### Modules

- Raw Domain
    - [x] MipiUnPack: Mipi原始数据转RAW16
    - [x] DePwl: 解压缩数据
    - [x] Dpc: 动态坏点校准（TBD）
    - [x] Lsc: 镜头阴影校准（TBD）
    - [x] Blc: 黑电平校准
    - [x] Rns: Raw域降噪
    - [x] WbGain: 白平衡增益
    - [x] Demoasic: 解马赛克
- RGB Domain
    - [x] Ltm: 局部色调映射
    - [x] RgbGamma: rgb伽马曲线
    - [x] Ccm: 色彩校准矩阵
    - [x] Rgb2Yuv: rgb域转yuv域
- YUV Domain
    - [x] YGamma: 灰度伽马曲线
    - [x] Contrast: 对比度提升
    - [x] Sharpen: 锐化边缘增强
    - [x] Cns: 颜色滤波（TBD）
    - [x] Saturation: 色度提升
    - [x] Yuv2Rgb: yuv域rgb域

<img src="https://github.com/BodhiHu/HDR-ISP/raw/main/docs/ISP/isp_result.png" />
# 训练检测模型

## 版本依赖
- VisionSeed固件版本 v1.3.2+

## 训练环境
- 腾讯云智能钛 tione

### 创建智能钛训练环境
1. 注册腾讯云账户
2. 搜索并打开 “智能钛机器学习平台”
3. 选择Notebook栏并新建一个Notebook，推荐配置1*V100或以上，存储大小50GB+
4. 短暂等待后，打开notebook
5. 点击“upload files”或直接拖拽文件将ipynb文件上传到服务器上
6. 根据notebook中的指示一步步完成训练过程

## 配置文件
下载目录下的custom_detection.json文件，可以更改label项来改变模型在客户端中显示的名字

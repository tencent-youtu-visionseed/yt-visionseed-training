# yt-visionseed-training

## 模型训练教程
- 检测模型：detection

## 部署模型到VisionSeed
所需材料：
- blob模型文件和json配置文件
- yt-visionseed-tool客户端
- VisionSeed

#### 上传
- 将blob和json文件放在同一目录下，并确保除了后缀以外两个文件名完全一致
- 打开yt-visionseed-tool客户端
- 选择端口并连接VisionSeed
- 进入“功能->AI模型配置”，点击“新增”
- 点击“打开”并选择json配置文件
- 点击“发送”，进度条结束后便可看到“自定义模型”下多出了新加的模型

#### 部署pipeline
- 在“功能->AI模型配置”栏目下，点击“重置空白”
- 将鼠标放在新增模型上，点击“使用”
- 将鼠标放在“摄像头”模块上，点击“拖拽连接”，并把线连接到新增的模型上
- 点击“写入”
# ChatGLM2+声音克隆 🎶
### 和喜欢的角色沉浸式对话吧：ChatGLM2-6B+声音克隆 🌟
## 如何使用 💡

(1) 在终端中运行
```
git clone https://huggingface.co/spaces/kevinwang676/FreeVC.git
cd FreeVC
pip install -r requirements.txt
```

(2) 在终端中运行
```
sudo apt update && sudo apt upgrade
apt install ffmpeg
```

(3) 在目录`./FreeVC/`下新建名为`checkpoint`的文件夹，并将`freevc-24.pth`文件上传至新文件夹。您可以通过[此链接](https://huggingface.co/spaces/kevinwang676/FreeVC/tree/main/checkpoints)下载`freevc-24.pth`文件。

(4) 在`./FreeVC/speaker_encoder/ckpt/`路径下找到并删除`pretrained_bak_5805000.pt`文件，将新版的`pretrained_bak_5805000.pt`文件上传至相同路径`./FreeVC/speaker_encoder/ckpt/`。您可以通过[此链接](https://huggingface.co/spaces/kevinwang676/FreeVC/tree/main/speaker_encoder/ckpt)下载新版的`pretrained_bak_5805000.pt`文件。

(5) 将此项目中的`app_new.py`文件上传至目录`./FreeVC/`下，在终端中运行`python app_new.py`。

(6) 完成！您现在就可以点击进入Gradio网页使用ChatGLM2-6B+声音克隆程序，和喜欢的角色开启沉浸式对话啦！

P.S. 本项目基于[ChatGLM2-6B](https://github.com/THUDM/ChatGLM2-6B)和[FreeVC](https://github.com/OlaWod/FreeVC)。

### 快速开始: [HuggingFace在线程序](https://huggingface.co/spaces/kevinwang676/FreeVC) 🤗

### AutoDL部署：[AutoDL镜像](https://www.codewithgpu.com/i/KevinWang676/ChatGLM2-Voice-Cloning/ChatGLM2-Voice-Cloning)，运行环境及文件均已配置好，可一键使用 ⚡

### 如果您喜欢这个程序，欢迎给我的Github项目点赞支持！ ⭐⭐⭐

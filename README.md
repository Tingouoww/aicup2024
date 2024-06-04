# aicup2024
> 2024 AICUP 影像資料生成競賽 實作紀錄

## 程式碼來源
- 本次競賽引用以下程式碼進行實作：
[pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix.git)
- 參考原始論文：Isola, P., Zhu, J.-Y., Zhou, T., & Efros, A. A. (2017). Image-to-Image Translation with Conditional Adversarial Networks. In Computer Vision and Pattern Recognition (CVPR), 2017 IEEE Conference on.
- 授權請參照LICENSE

## 訓練環境
- 使用**Google Colaboratory**作為訓練平台
- 作業系統：Ubuntu 22.04.3 LTS
- Python版本：Python 3.10.12
- GPU：NVIDIA A100-SXM4-40GB / Tesla T4
- 所需套件詳見 **requirements.txt** / **environment.yml**

## 文件說明
- 各程式檔案使用說明請參考 [overview.md](docs/overview.md)
- 競賽程式碼及其相關說明請直接下載 [aicup2024.ipynb](aicup2024.ipynb) 或進入下方雲端連結直接使用
- 競賽報告請至 [競賽報告_TEAM_5556](競賽報告)
- 模型權重請參考 [模型權重設定檔](模型權重設定檔)

## 大型檔案雲端連結
[GOOGLE CLOUD](https://drive.google.com/drive/folders/1-jQx8Z9FtfxWSRHC5nv1TgTz36S0h308?usp=drive_link)
- 雲端檔案中含有雲端檔案說明，請參閱雲端檔案使用
- 雲端中包含已完成前處理之資料集、按照道路與河流完成分類的原始資料集、繳交成果運用之模型檔案
- 同時，由於使用colab環境運行程式，故雲端中也存了一份競賽程式碼

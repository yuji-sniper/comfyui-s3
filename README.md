## custom_nodeへの配置手順
```sh
cd ComfyUI/custom_nodes

git clone https://github.com/yuji-sniper/comfyui-s3.git comfyui-s3

cd comfyui-s3

pip install requirements.txt

# S3_REGION, S3_BUCKET_NAMEを設定
vi .env
```

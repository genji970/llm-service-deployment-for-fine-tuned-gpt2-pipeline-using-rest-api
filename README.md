# for-llm-service-deployment
api code for llm pipeline

`docker pull ghcr.io/genji970/api_image:latest`

collecting pdf data -> fine tuning -> rest api -> deploying in aws

1) deploying in aws step is not yet done

2) llm-building pipeline is from https://github.com/genji970/llm_data_collecting-processing_inference

3)there's no saved model in this repo. git clone 2)'s link and type `python -m llm_project_train.master.main True` in terminal. then saved model will be made. But 3) step is unnecessary for using this api

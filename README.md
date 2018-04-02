yzm_recognition

gcloud ml-engine jobs submit training beta330  --module-name trainer.task --staging-bucket gs://yzm_bucket --package-path /Users/wenlu/PycharmProjects/Google_Cloud_Compute_Engine/yzm_recognition/trainer --python-version=3.5 --runtime-version=1.6 --config /Users/wenlu/PycharmProjects/Google_Cloud_Compute_Engine/yzm_recognition/trainer/config.yaml


please reference this article-->http://www.cnblogs.com/duwenlu/p/8704258.html

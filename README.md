# arcface_TF1
оригинал - https://github.com/luckycallor/InsightFace-tensorflow 

претренерованную модельску скачать тут https://drive.google.com/file/d/107Qu56o1IwQxH61Q6smZk-DO2-xU6EwE/view

исправлена первоначальная работа с img (было на старой версии сайкитлёрна, теперь на матплотлибе и пиллоу

запуск:

python get_embd.py --config_path=./configs/config_ms1m_100.yaml --model_path=pretrained_model/best-m-10060001 --read_path=face.jpg --save_path=saving/embd.pkl

или просто python get_embd.py

в консоль ембениги пишет (можно поправить, что бы в отдельный файлик писал их сразу)

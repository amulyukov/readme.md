### В директории терраформа будут игнорироваться следующие файлы и каталоги:

## 1 локальные директории .terraform

## 2 Файлы в которых встречаются .tfstate или .tfstate.

## 3 Файл с названием crash.log

## 4 Файлы в которых встречаются в названии .tfvars

## 5 Файлы override.tf, override.tf.json и в которых встречаются в названии *_override.tf, *_override.tf.json

## 6 Файлы .terraformrc и terraform.rc

# Infrastructure As Code

> Для начала работы установите следующие env переменные, получить их можно при установке yandex cloud cli

- export TF_VAR_yc_token= тот же токен что при установке cli

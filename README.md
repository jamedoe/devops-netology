1. Игнорирование любых папок .terraform
2. Игнорирование любых файлов, содержащих в названи .tfstate
3. Игнорирование файлов вылета crash.log
4. Игнорирование .tfvars файлов (судя по комментарию, там могут лежать авторизационные данные)
5. Игнорирование файлов override.tf (но почему нельзя было использовать маску из *?)
6. Игнорирование конфигурационных файлов .terraformrc, terraform.rc

Есть закоментированная возможность убрать из игнорирования файлы override. 
Там указан буквально пример: example_override.tf

Есть закомментированная возможность игнорировать фпйлы tfplan


# Исключить директории .terraform где либо размещенные 
**/.terraform/*

# Игнорировать файлы .tfstate 
*.tfstate
*.tfstate.*

# Игнорировать файл crash.log, все файлы с именем crash и с любым расширением, 
crash.log
crash.*.log

# Игнорировать все файлы .tfvars, которые могут содержать пароли, конфиденциальную информацию 
*.tfvars
*.tfvars.json

# Игнорировать файлы файлы переопределения, которые используются для переопределения ресурсов локально 
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Игнорировать файлы конфигураций
.terraformrc
terraform.rc

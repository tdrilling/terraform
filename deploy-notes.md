✅ Features:

Erstellt Ubuntu 24.04 LTS VM in Azure
Installiert LAMP-Stack (Apache, MySQL, PHP) via Cloud-Init
Nutzt base64encode() für custom_data (Azure-konform)
Enthält Variablen für Standort, Resource Group, VM-Name, Größe, Admin-User und Passwort
Erstellt VNet, Subnetz, NSG (SSH & HTTP), Public IP, NIC

Hier ist die vollständige Terraform-Datei für eine Ubuntu 24.04 LTS VM auf Azure mit:
✅ WordPress + phpMyAdmin via Cloud-Init
✅ Passwort-Login (kein SSH-Key)
✅ NSG-Regeln für SSH (22) und HTTP (80)
✅ Cloud-Init korrekt Base64-codiert


terraform init
terraform plan
terraform apply -auto-approve

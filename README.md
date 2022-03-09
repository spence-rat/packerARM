# packerARM

az cli to create machine from image:

az vm create --name <nameOfMachine> --location <location> --image <nameOfImage> --admin-username <admin name> --admin-password <password> --plan-name pro-preview --plan-product windows10preview  --plan-publisher microsoft-hyperv -g <resourceGroup> --public-ip-sku Standard

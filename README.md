# FSWD-AZURE-JUN-2026-AM

### Setup student azure portal

[Student Portal](https://azure.microsoft.com/en-us/free/students)

- Click start free

![](/Assets/az-student-login-0.png)

- login using the student id

![link](/Assets/az-student-login-1.png)

![](/Assets/az-student-login-2.png)

![](/Assets/az-student-login-3.png)

![](/Assets/az-student-login-4.png)

![](/Assets/az-student-login-5.png)

![](/Assets/az-student-login-6.png)

![](/Assets/az-student-login-7.png)

![](/Assets/az-student-login-8.png)

![](/Assets/az-student-login-9.png)

![](/Assets/az-student-login-10.png)

![](/Assets/az-student-login-11.png)

## Azure Home Page

[Potal Home](https://portal.azure.com/#home)

![](/Assets/az-student-login-12.png)

## Check the Azure Balance

![check balance](/Assets/az-balance-check-1.png)

## Finding the regions allowed for your Subscription

- Start the Azure Cloud Shell and select the bash shell

![azure shell](/Assets/starting-cloud-shell.png)

```
az policy assignment list \
  --query "[?contains(displayName, 'Allowed')]" \
  -o table
```

```
az policy assignment list -o json
```

![](/Assets/allowed-regions-1.png)


- You can see the list of allowed regions

![](/Assets/allowed-regions-2.png)

## Creating a VM in Azure

![](/Assets/vm-0.png)

![](/Assets/vm-1.png)

![](/Assets/vm-2.png)

![](/Assets/vm-3.png)

![](/Assets/vm-4.png)

- Select review+create

![](/Assets/vm-5.png)

- If the validation passed, select create VM.

![](/Assets/vm-6.png)

## Connectect to the VM

![](/Assets/connect-vm-1.png)
![](/Assets/connect-vm-2.png)
![](/Assets/connect-vm-3.png)
![](/Assets/connect-vm-4.png)
![](/Assets/connect-vm-5.png)
![](/Assets/connect-vm-6.png)
![](/Assets/connect-vm-7.png)
![](/Assets/connect-vm-8.png)

## Verify IIS Works Locally on the VM

```
Get-WindowsFeature Web-Server
```
![](/Assets/install-iis-1.png)
![](/Assets/install-iis-2.png)

```
Install-WindowsFeature -Name Web-Server -IncludeManagementTools
```
![](/Assets/install-iis-3.png)
![](/Assets/install-iis-4.png)
![](/Assets/install-iis-5.png)
![](/Assets/install-iis-6.png)

## Open HTTP/HTTPS port 80 on the VM

![](/Assets/enable-http-port-1.png)
![](/Assets/enable-http-port-2.png)
![](/Assets/enable-http-port-3.png)

### Upload the website(jobzila)

![](/Assets/upload-jobzila-1.png)
![](/Assets/upload-jobzila-2.png)
![](/Assets/upload-jobzila-3.png)
![](/Assets/upload-jobzila-4.png)
![](/Assets/upload-jobzila-5.png)
![](/Assets/upload-jobzila-6.png)
![](/Assets/upload-jobzila-7.png)
![](/Assets/upload-jobzila-8.png)
![](/Assets/upload-jobzila-9.png)
![](/Assets/upload-jobzila-10.png)


## Delete the VM/Resource Group

![](/Assets/delete-rg-1.png)
![](/Assets/delete-rg-2.png)
![](/Assets/delete-rg-3.png)
![](/Assets/delete-rg-4.png)

## Creating a SQL Server Database

![](/Assets/sql-server/sql-server-1.png)
![](/Assets/sql-server/sql-server-2.png)
![](/Assets/sql-server/sql-server-3.png)
![](/Assets/sql-server/sql-server-4.png)
![](/Assets/sql-server/sql-server-5.png)
![](/Assets/sql-server/sql-server-6.png)
![](/Assets/sql-server/sql-server-7.png)
![](/Assets/sql-server/sql-server-8.png)
![](/Assets/sql-server/sql-server-9.png)
![](/Assets/sql-server/sql-server-10.png)
![](/Assets/sql-server/sql-server-11.png)
![](/Assets/sql-server/sql-server-12.png)
![](/Assets/sql-server/sql-server-13.png)
![](/Assets/sql-server/sql-server-14.png)
![](/Assets/sql-server/sql-server-15.png)
![](/Assets/sql-server/sql-server-16.png)
![](/Assets/sql-server/sql-server-17.png)
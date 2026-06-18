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
![](/Assets/vm-5.png)

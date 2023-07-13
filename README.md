# Terraform

![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/dbf7d536-737d-46f6-ad6b-061fa9c23824)

## 1) Installation on Ubuntu

#### Installed the gnupg, software-properties-common, and curl packages
```
sudo apt-get update && sudo apt-get install -y gnupg software-properties-common
```

#### Install the HashiCorp GPG key.
```
wget -O- https://apt.releases.hashicorp.com/gpg | \
gpg --dearmor | \
sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg
```

#### Verify the key's fingerprint.
```
gpg --no-default-keyring \
--keyring /usr/share/keyrings/hashicorp-archive-keyring.gpg \
--fingerprint
```

#### Add the official HashiCorp repository to your system
```
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] \
https://apt.releases.hashicorp.com $(lsb_release -cs) main" | \
sudo tee /etc/apt/sources.list.d/hashicorp.list
```
#### Download the package information from HashiCorp.
```
sudo apt update
```
#### Install Terraform from the new repository.
```
sudo apt-get install terraform
```


![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/8f66ee32-004c-4455-9ddf-f17590d2e1f1)

![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/d262bbce-e325-404b-9771-87ed39d86fbc)

![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/3c340188-fbec-4734-b5d0-003eb6c22930)



## 2) Commands 

#### Check the version of Terraform
```
terraform --version
```
![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/2dfe7df8-5058-4233-9570-6633ef0acf72)


#### Validate Terraform
```
terraform validate
```
#### Initialize Terraform
```
terraform init
```
![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/9868b387-469f-4463-be49-66bfface87d8)

![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/19a35392-425b-4c43-88d9-953529509589)

#### Terraform Plan Command

```
terraform plan
```
![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/7370a03e-08e3-45a4-9aa1-ad674e46988b)

#### Terraform Apply

```
terraform apply
```
#### Output
![image](https://github.com/DhanashriSaner/Terraform/assets/88526990/8ea7e70f-7cb6-4d55-8b73-97352de8eb17)



    }
  ],
  "check_results": null
}




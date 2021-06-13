---
description: Use GCP to Mine Meson
---

# Google Cloud Platform

### **In order to make the best use of resources, we hope that you can use idle terminals to deploy the Meson project.** 

### **But if you like to try, here are the instructions for you. You could register GCP, and start your own project, while mining Meson at the same time.**

## Step1, Register

Open Google Cloud Platform \(GCP\) website [https://cloud.google.com/](https://cloud.google.com/)

![https://cloud.google.com/](https://lh3.googleusercontent.com/BFEuYjyKdigUxh6uosA1V-lniOLOosWFKzpLn0uy8zC-EVnSKHKKB-mNT1ncu9GhKIIcbDgGoQbfVtDGfFqXVBcNdYg8HEnHNWSfcVbxzl5f9bY_9Q9nPLYeT3ZrTsLEwZj4C005)

Follow the instructions, filling your phone number and credit card \(Mastercard \| Visa\), and you will get a $300 trial for 90 Days.

## Step2,  Create the Instance Templates

1. Open the navigation Menu  -&gt;  Click “Compute Engine”  -&gt;  Click “instance templates”

![](https://lh4.googleusercontent.com/VrX5H6dPh9GP2eXCVUHo9BQO4s1g7FQ5YCjwjak6x-uUeRT6WM4rgMMM1T3qERVtcwLF7wh-A7JVicL6Y9oIh9s096UnNVCGuEcG5j9b2AmouJS4iMFpm38gsLgLbrrTyAtqjR8q)

1.Create Instance Template

![](https://lh6.googleusercontent.com/TWIvG7PKv5You3pCiAa9G8CoExQVBV9xp59Xd90zqNeXf7ZRMFGuQ5_QdMqGmHQnwGqrjDCOTHMZ0NtbvkjDP98wtttcHbPrDfgaeXTXu37uxOdpYGOpBd40EkZ13a-MznmQ2LSu)

![](https://lh5.googleusercontent.com/e0_M_kKDB2G5mojHWBAEDuHKUmuS0EZDVTgegkgufxdvNzMT4yIdqtHCOjqPjbbaJaXK_DvGl3LDl8hqXDtuSavTAGphQVItesA5_SXlp0va8cOAZeRmYbGQ8hJn--e3PABx0XFk)

2.Change The disk into at least 50 GB

![](https://lh3.googleusercontent.com/c0iDFahZjwvU_8CYaiPQeLcw0iFwxwrHX-An5aAud3QJ5aMQwaRuArE9hgI_BTp4oQ3SOmZPp6z6PAhH41pKe9ZmGXiCVNJOrBpO08WC7pL9zJoaBU0WEroWeTi3_nGY_HLjG0IL)

![](https://lh6.googleusercontent.com/SGPt4I2QDDafSoTxgnHhcKlfDUYqpcNxwEya0cflHOnx_ziE2gQRPzZL6ailVwqvtd2PgyoBrcY_5NI2C3eCzmX4BC7WeVzKEGDVqqWfA8UVKxSW79Pq2niLx3wHIsu6G3le3t2a)

3.Add a network tag “meson” to open a port for the need of Meson Network.

![](https://lh6.googleusercontent.com/s8YM9_0mUK4y9hOZUUSMZr9-ZR8qOADnYorAsvNWXPrqVCAkpVWjZSRILo3xTNNCC6Q3eLDsuvaJyDpACTSA5A71-oUw6qbtQ4_jaPYlaPNiaao1J01o7w5IiYh4-jio3BksSAZm)

![](https://lh5.googleusercontent.com/rMOfc7HfnnRL6F1ErpICXYdDboLaHdgHdXiJRwhqW-qVskIzBNkDS665cdGBCvuqbL5NAZC12d4tN4K40aQ2nVrhZco1wf8K-wy-AlfZwGjCSEk5pUpBDjDoN4Buf7PcuRgzgVdy)

## Step3, Explain for the Network Tag you just added called “meson”

![](https://lh5.googleusercontent.com/MH0t9dGPi5qtpjPMa0_N93xtajemPXMPs4skjf3FRwzUCSKH42wtdHtmzp9uUrE8A0DUJhD-DMS7EtLRsgrKGVVH-lzSH2m03SqwNPpwd8MlwfLQ7hNRtPsdxSm514XzK-SD-Om7)

![](https://lh5.googleusercontent.com/B8TdJTapBkzNYcbO0NJH8sALWdjvSij6PLebmx52VLspqvdjeEgcPvBeESJrDuvNi-R5bsvL4v1SNy3yxCMcT16Y1XuWuicrrFeNDhD3czqyv8-_T-AjZcVyN0f1HGNHIQTWVBBP)

![](https://lh5.googleusercontent.com/bKiMdxpc7ezMiCGDHQiNNIsRrPAE32tJ6Rrg0rL_4OxAef4MLfSNBsraAD8QxefO4acLV_KtkB89nj6vpHpQG_6WhMze_W0q70vNZWz7om2F7M1QU8j3k97rywJZITmg-aB7iA0g)

The above is a simple reference that opens port 19091 for TCP connection.

## Step4, Create a VM instance from meson-template

![](https://lh4.googleusercontent.com/e0gnXfoaQipEkDhrdGJgtEBw8xHB0Q47OEz12vzstfp_FH9Blz4dZUrwAtjYfK7wnkX01RrbqkzxdkHjNQ7kNnUILrqo-FizjjSbgi0fgn1XM4kQbeB_t7iVgbPV-SB4bNDF3YPq)

![](https://lh4.googleusercontent.com/3EjV9Ya5WpNBWMqv_qej2kCZ0DgHU-zJI10Ebs5S0bwtqmSU-9a2pH16tXh-lT7PNqAcfreQ-7ddC9PjuJm_7FxDx4Za62uxXwzxKCCszPJXo1nnWLspkOOzFWA-H_JeZjM98E2V)

![](https://lh4.googleusercontent.com/BL66Ysp9weNgSD2PZrcMlJKX4ta6tUxq2y3TucHMEBzFSXedUz3_SVSdVeNW0NvR33p1kBf_kBmBgy2CwxJXZqQQrMyX843wT-vBsOS60yhthdGd8SHwn3PLwVqm1MsWGJKWgPHs)

As we have finished the template, it’s cool to simply click Create.

![](https://lh3.googleusercontent.com/yoUY9GMIjSvUAIl6VwjNZHVm9UNpsQCKyBiprgkrrj7JhIMYEZY5ldzGIMtDUmRpwaAZFcQgs2-LNK39Hv3bwRyyf3slJu93F4yI_-Rytiebw9Rfhdgq2UtIWQlbH2OPFVDB02Lo)

## Step5, Click SSH to connect to your server to finish the deployment 

![](https://lh3.googleusercontent.com/YY7tAWPzRPOziSZ21redgIeD0CtEN-r8UgBYq-zVulssJn-Eis8hn9N9yrK478AusT48jAUHeGddQimAKLNrkGkwpnt0gxvmFCWIrk6ECeRqFKc2wIRn-V1relc87R18gIyAs3ez)

Follow the steps from “[https://meson.network/terminals](https://meson.network/terminals)” to deploy your server as a Meson terminal.

```text
####### Tutorial: How to install and run miner terminal on linux server#######
Please make sure the port you use is opened on the firewall and sudo permission can be used
#Step.1 download the terminal package
$ wget 'https://assets.meson.network:10443/static/terminal/v2.5.1/meson-linux-amd64.tar.gz'
#Step.2 unzip the package
$ tar -zxf meson-linux-amd64.tar.gz
#Step.3 install the app as service
$ cd ./meson-linux-amd64
$ sudo ./meson service-install
#Step.4 input your token, port and space provide
#Step.5 start the app
$ sudo ./meson service-start
#Step.6 wait about 1 minutes and check status
$ sudo ./meson service-status
after 2-3 minutes you will have a new terminal record
#Step.7 check your earnings
### Other commands ###
"sudo ./meson service-stop" to stop app
"sudo ./meson service-remove" to remove app

( this is current instruction for a Linux 64 bit server [05/27/2021] )
```

And you could see your servers working ON as Meson Note on the same page.

![](https://lh6.googleusercontent.com/By_Vwucqe-qFyQMgZATpLMVwqNYj4m8GneRri8t-iKOTV1TOKrV5Gm1lbcHcorImeHu6JEmGCmRqjNA26I63MUqiK3d2N7c7KlSCyqFWIvXn8HyxApi7rwTdWvbwJbEQCz5BBetb)

Congratulations if you have arrived here!

## Any Questions?

Website: [https://meson.network/](https://meson.network/)

Discord: [https://discord.com/invite/z6YfSHDkmS](https://discord.com/invite/z6YfSHDkmS)

Telegram: [https://t.me/mesonnetwork](https://t.me/mesonnetwork)

## Please be aware of the traffic price

[https://cloud.google.com/vpc/network-pricing](https://cloud.google.com/vpc/network-pricing)

![](https://lh4.googleusercontent.com/qV1oYOUUh4zbxAlhnQ5WfXWruCxT9l9pWoOAMc6m1aEfuedpY7XYDY9HBD6sLjQPMU8mla_BzkSAMIrk4laX1kzPMMO5DnsKFGWQaXjUtsLMfNYyrLP9VJhj_iob-5jqqF8f3Xjs)

![](https://lh6.googleusercontent.com/plsuqeH1aLPmcznSK8u_3yx3OjPukzSZmRGnrelsCoX7qqn_XbK5jxal5_QCa007Ot45JzhPyH0wkQmS2ClzUdNmqWmCX138nVl5xAeJ4qJ2dENkwKYA64GLeglEJ5QA2zE2wrCG)


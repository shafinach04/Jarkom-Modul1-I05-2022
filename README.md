# Jarkom-Modul1-I05-2022

| Name | NRP |
| ------ | ------ |
| Amelia Mumtazah Karimah | 5025201128 |
| Shafina Chaerunisa | 5025201129 |
| Muhammad Fadli Azhar | 5025201157 |

# Distribution Parts

1. Muhammad Fadli Azhar : Number 1-4
2. Amelia Mumtazah Karimah : Number 5-7
3. Shafina Chaerunisa : Number 8 - 10

## 1
## Question
Mention the web server used on "monta.if.its.ac.id"

## Answer

## 5
## Question
Filter so that wireshark only picks up packets coming from port 443!


## Answer
To filter the port that it only picks up coming from port 443 type into the filter bar: "tcp.srcport == 443"

## 6
## Question
Filter so that wireshark only shows packets going to lipi.go.id !

## Answer
To find packet lipi.go.id, we filter with “tcp contains lipi.go.id”

## 7
## Question
Filter so that wireshark only picks up packets coming from your ip!

## Answer
First, open terminal and find the IP Address with command "ifconfig en0".


Copy the IP Address and also open Wireshark, then insert "ip.src == own IP Address" into filter bar.



## 8
## Question
Browse the flow of packets in the given .pcap file

## Answer
I was looking through one by one in info section. Found in the tcp.stream eq 12. The .pcap file was in it and by click right choose Follow -> TCP Stream will show the conversation between two students regarding cheating in practicum activities.

<img width="638" alt="conv" src="https://user-images.githubusercontent.com/112922727/192083018-a0be505c-50ab-499c-89ed-7638db53a682.png">

## 9
## Question
Name the file found in the format [group_name].des3 and save the output file with the name “flag.txt”

## Answer
Saving the decrpty file in stream 29 which contain text like this that have to be decrypt and guess the password of the file. Save the data/file as io5.de3.

<img width="633" alt="stream29" src="https://user-images.githubusercontent.com/112922727/192083166-7cdec58f-0945-45cf-8f85-76d2eff5f320.png">

## 10
## Question
Find the secret password (flag) of the above-mentioned underground organization!

## Answer
I already tried to decrypt through command prompter but failed since its stated cannot open the file.
<img width="670" alt="cannot" src="https://user-images.githubusercontent.com/112922727/192083549-a4f4cc2f-8cb7-469e-bdf4-4c7ccc8153ab.png">



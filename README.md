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
To find the web server that is used type into the filter bar ==http.host == monta.if.its.ac.id
![1664010125784](https://user-images.githubusercontent.com/100435004/192090048-41492745-676e-434b-a760-c7cc99ffb07e.jpg)


Then click right on the blue highlight and click follow & choose TCP Stream





## 5
## Question
Filter so that wireshark only picks up packets coming from port 443!
## Answer
To filter the port that it only picks up coming from port 443 type into the filter bar: "tcp.srcport == 443"
![Screen Shot 2022-09-24 at 14 42 48](https://user-images.githubusercontent.com/112918215/192086717-6b2f782b-1b4b-44ab-b1df-2f1d483eed18.jpeg)

## 6
## Question
Filter so that wireshark only shows packets going to lipi.go.id !
## Answer
To find packet lipi.go.id, we filter with “tcp contains lipi.go.id”
![Screen Shot 2022-09-24 at 14 47 06](https://user-images.githubusercontent.com/112918215/192086896-1cfa08af-f271-41d2-92cf-4ae5d909e2e8.jpeg)

## 7
## Question
Filter so that wireshark only picks up packets coming from your ip!
## Answer
First, open terminal and find the IP Address with command "ifconfig en0".
![Screen Shot 2022-09-24 at 14 50 33](https://user-images.githubusercontent.com/112918215/192087144-f2f1f989-9fa1-48a5-8aac-5ceb8804d04f.jpeg)
Copy the IP Address and also open Wireshark, then insert "ip.src == own IP Address" into filter bar.
![Screen Shot 2022-09-24 at 14 53 01](https://user-images.githubusercontent.com/112918215/192087148-88f4d271-f97d-479b-a7ad-c312d5440c96.jpeg)

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



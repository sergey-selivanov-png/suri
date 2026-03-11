# "Домашнее задание к занятию «Защита сети»" - Selivanov Sergey.

---
### Задание 1

Suricata:

![Скриншот 1](https://github.com/sergey-selivanov-png/suri/blob/main/image/g1.png)

Suricata обнаружила все сканирования, кроме TCP ACK (-sA) сканирования. Данный вид сканирования используется для определения фильтрации и выполняется без установления соединения. 

Fail2Ban:

![Скриншот 2](https://github.com/sergey-selivanov-png/suri/blob/main/image/g2.png)

Fail2Ban не обнаружил не одного сканирования, так как при сканировании не выполнялся процесс аутентификации. 

---
### Задание 2

Suricata:

![Скриншот 3](https://github.com/sergey-selivanov-png/suri/blob/main/image/g3.png)

Suricata обнаружила вторжение с указанного в логах ip адреса.

Fail2Ban:

![Скриншот 4](https://github.com/sergey-selivanov-png/suri/blob/main/image/g4.png)

Fail2Ban обнаружил попытку подбора учетных данных и заблокировал ip адрес, с которого была произведена атака. 

---

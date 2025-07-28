<img width="1011" height="313" alt="image" src="https://github.com/user-attachments/assets/7dfecb3a-e05c-4ef2-b329-707f6359ab14" /><br>
/22代表子网掩码长度是22，即前22位固定，后10位可变，是主机部分，网段可用主机数为2^可变位数-2<br>
全0用来标识整个网段，但不是网关，全1是广播地址，发送消息给全1地址，即可实现广播功能<br>
网关常被设为第一个可用ip，例如：172.16.8.1<br>

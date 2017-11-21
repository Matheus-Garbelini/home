---
title: "GREYHOUND: Directed Greybox Wi-Fi Fuzzing"
publishDate: 2019-08-06
authors: ["M. E. Garbelini", "C. Wang", "S. Chattopadhyay"]
publication_types: ["2"]
abstract: "The recent rise in complex Wi-Fi vulnerabilities indicates the critical need for effective Wi-Fi protocol testing tools. We present a directed fuzzing methodology named GREYHOUND that automatically tests the Wi-Fi client implementations against vulnerabilities like crashes or non-compliant behaviours. Leveraging a holistic Wi-Fi protocol model, GREYHOUND directs the fuzzer in specific states of target Wi-Fi client. By exchanging mutated packets with a Wi-Fi client, GREYHOUND aims to induce the client to exhibit anomalous behaviours that badly deviate from Wi-Fi protocols. We have implemented GREYHOUND and evaluated it on a variety of real-world Wi-Fi clients, including smartphone, Raspberry Pi, IoT device microcontrollers and a medical device. Our evaluation indicates that GREYHOUND not only automatically discovers known vulnerabilities (including KRACK and Dragonslayer) that would require specialized verification otherwise, but, more importantly, it also has uncovered four new vulnerabilities in popular Wi-Fi clients. All discovered vulnerabilities are confirmed by manufacturers and assigned three different common vulnerability exposures. Furthermore, our evaluation with three existing Wi-Fi fuzz testing tools reveals that they fail to discover any of the vulnerabilities uncovered by GREYHOUND. Last but not the least, we have deployed GREYHOUND to discover KRACK and DragonSlayer within the Wi-Fi client implementation of automotive head units."
featured: false
publication: "*IEEE Transactions on Dependable and Secure Computing*"
fixed_url_pdf: "https://ieeexplore.ieee.org/abstract/document/9160891"
---


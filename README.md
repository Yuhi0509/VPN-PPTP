# VPN架設-PPTP

<!-- vim-markdown-toc GFM -->
* [甚麼是VPN]
* [甚麼是PPTP]
* [實作步驟]

<!-- vim-markdown-toc -->.

##　甚麼是VPN
虛擬私人網路，又稱為虛擬專用網路（英文︰Virtual Private Network，簡稱VPN），是一種常用於連接中、大型企業或團體與團體間的私人網路的通訊方法。虛擬私人網路的訊息透過公用的網路架構（例如：網際網路）來傳送內聯網的網路訊息。虛擬私人網路利用已加密的通道協議（Tunneling Protocol）來達到保密、傳送端認證、訊息準確性等私人訊息安全效果。若使用得法，這種技術可以用不安全的網路（例如：網際網路）來傳送可靠、安全的訊息。需要注意的是，加密訊息與否是可以控制的。沒有加密的虛擬私人網路訊息依然有被竊取的危險
##　甚麼是VPN
點對點隧道協議（PPTP，Point to Point Tunneling Protocol）是一種主要用於VPN的傳輸層網路協議。PPTP的協定規範本身並未描述加密或身份驗證的特性，然而常見的如Microsoft Windows帶有的實現都具備這些。PPTP以GRE（Generic Routing Encapsulation）協定向對方作一般的點對點傳輸。通過TCP1723埠來發起和管理GRE狀態。因為PPTP需要2個網路狀態，因此會對穿越防火牆造成困難。很多防火牆不能完整地傳遞連線，導致無法連接。這經常發生在Windows或Mac OSPPTP可配合MSCHAP-v2或EAP-TLS進行身份驗證 。使用VPN可配合微軟點對點加密〈MPPE〉進行連接時的加密。

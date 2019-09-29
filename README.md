# Windows 透過 Hyper-V 安裝 Ubuntu 18.04

* [Youtube Tutorial - Windows 透過 Hyper-V 安裝 Ubuntu 18.04](https://youtu.be/KHjcVP6fSo4)

## 前言

之後會有一些影片使用 Linux 做教學，因為不少東西是只有在 Linux 上可以安裝，

甚至在 Linux 上安裝比較不會有問題，而且工程師肯定要學 Linux 的:satisfied:

所以這篇文章我們就先從最簡單的安裝 Ubuntu 18.04 開始吧:smile:

首先，你的 Windows 版本一定是要專業版，否則可能會沒有 Hyper-V。

為什麼要使用 Hyper-V 安裝 Ubuntu 呢:question:

為什麼不使用 VirtualBox :question:

( 我假設大家的 Windows 中都有安裝 docker，所以肯定會有 Hyper-V )

如果你不知道什麼是 docker，可參考我之前的文章:thumbsup:

[Docker 基本教學 - 從無到有 Docker-Beginners-Guide](https://github.com/twtrubiks/docker-tutorial)

原因很簡單，在 Windows 中 Hyper-V 和 VirtualBox 會互相衝突:scream:

所以說，如果你有在本機安裝 docker，就只能透過 Hyper-V 安裝 Ubuntu。

除非，你電腦上不安裝 docker ( 也就不會有 Hyper-V )，這樣就可以安裝

VirtualBox，然後裡面再安裝 docker 也是可以:sweat_smile:

但這裡，我們將使用 Hyper-V 安裝 Ubuntu 18.04:relaxed:

## 教學

先確認自己的電腦是否有開啟 Hyper-V，

( 如果沒有開啟，第一次開啟可能需要重開機 )

![alt tag](https://i.imgur.com/krMEgVu.png)

找到 Hyper-V 管理員

![alt tag](https://i.imgur.com/uTuzclr.png)

A 的部分其實就是 docker 的 VM。

這邊我們點選快速建立，

![alt tag](https://i.imgur.com/73kl391.png)

選擇 Ubuntu 18.04，

![alt tag](https://i.imgur.com/a3FQrlX.png)

第一次下載會比較慢，請耐心等待，

![alt tag](https://i.imgur.com/uG1J3Ax.png)

下載完畢後會看到這個畫面，

![alt tag](https://i.imgur.com/ejv7lJi.png)

你可以點選編輯設定去改一些東西，

像是 RAM 或 CPU 之類的，

(也可以之後在修改，VM 在關閉的情況下都可以修改 )

![alt tag](https://i.imgur.com/1JSCQuw.png)

點選連線後會看到這個畫面，請選啟動

![alt tag](https://i.imgur.com/8sal6YF.png)

順利看到 Ubuntu 18.04 安裝畫面，

![alt tag](https://i.imgur.com/Ph44zMq.png)

設定你的帳號密碼，

![alt tag](https://i.imgur.com/PbjEICe.png)

點選下一步，

![alt tag](https://i.imgur.com/ifZdftZ.png)

安裝完後點選連線，

![alt tag](https://i.imgur.com/WDU8pdT.png)

會跳出這個頁面讓你輸入帳號密碼

![alt tag](https://i.imgur.com/pAzp88z.png)

如果正確無誤，就可以順利進入系統了

![alt tag](https://i.imgur.com/NRd0BLp.png)

## 後記

終於可以開始玩 Linux 了，這篇文章是教大家使用 Hyper-V 安裝，不過我有時候總是會覺得不太穩，

我有一台 Windows 電腦是本機沒安裝 docker，然後就可以安裝 VirtualBox，再裝 Ubuntu 18.04，裡面

安裝 docker 也沒什麼問題，唯一需要注意的就是 ram 要多一點:smile:


## Donation

文章都是我自己研究內化後原創，如果有幫助到您，也想鼓勵我的話，歡迎請我喝一杯咖啡:laughing:

綠界科技ECPAY ( 不需註冊會員 )

![alt tag](https://payment.ecpay.com.tw/Upload/QRCode/201906/QRCode_672351b8-5ab3-42dd-9c7c-c24c3e6a10a0.png)

[贊助者付款](http://bit.ly/2F7Jrha)

歐付寶 ( 需註冊會員 )

![alt tag](https://i.imgur.com/LRct9xa.png)

[贊助者付款](https://payment.opay.tw/Broadcaster/Donate/9E47FDEF85ABE383A0F5FC6A218606F8)

## 贊助名單

[贊助名單](https://github.com/twtrubiks/Thank-you-for-donate)

## License

MIT license
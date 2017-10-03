vdstat
===================

vdstat is the server statistics table monitor for SYSTEM ADMIN LINUX SERVER, purposes support detection DDoS attacks into your server.

----------

1. Get vdstat English language version:
-------------
```
curl -L https://github.com/duy13/VDSTAT/raw/master/vdstat-en -o /usr/bin/vdstat
chmod 700 /usr/bin/vdstat
/usr/bin/vdstat
```
----------


2. Tải vdstat Bản Tiếng Việt:
-------------
```
curl -L https://github.com/duy13/VDSTAT/raw/master/vdstat-vn -o /usr/bin/vdstat
chmod 700 /usr/bin/vdstat
/usr/bin/vdstat
```

Program interface:
-------------
```
########### The server statistics table for SYSTEM ADMIN LINUX SERVER VO DUY DOT COM: ########### TIME:21H31-DATE:18-02-2017 ###########

        CPU usage: ~0.00%       RAM usage: ~3673MB                              IO usage:       ~0MB/s READ
                                                                                                ~2MB/s WRITE
        The total number of QUERIES to port 80 is: 47   (By 17 IP Address request)
        The total number of QUERIES to port 443 is: 0   (By 1 IP Address request)

         Total number of ESTABLISHED connections is:                    |       Network Bandwidth:
         Port 80: 4 connections                                         |       Incoming: 140KB/s
         Port 443: 0 connections                                        |       Outgoing: 709KB/s

IP Address request much:
     50 112.8.43.10 www.voduy.com
     23 5.188.211.10
      6 123.21.66.90
      4 127.0.0.1 localhost
      3 113.181.151.7 localhost
      2 123.30.175.204 bot34.coccoc.com
      1 94.100.181.37 picker1.i.mail.ru
      1 66.249.79.168 crawl-66-249-79-168.googlebot.com
      1 66.249.79.160 crawl-66-249-79-160.googlebot.com
      1 66.249.79.150 crawl-66-249-79-150.googlebot.com
      1 66.249.79.124 crawl-66-249-79-124.googlebot.com
      1 66.249.79.108 crawl-66-249-79-108.googlebot.com
      1 46.229.168.74
      1 46.229.168.70
      1 46.229.168.69
      1 40.77.167.29 msnbot-40-77-167-29.search.msn.com
      1 222.254.217.10 static.vnpt.vn
      1 216.169.110.193 216-169-110-193-cust-gw.reverse.ezzi.net
      1 157.55.39.220 msnbot-157-55-39-220.search.msn.com
      1 115.78.206.110 adsl.viettel.vn
      1 113.190.224.249 static.vnpt-hanoi.com.vn

Thank you for using!

```


Giao diện chương trình:
-------------
```
########### Bảng thống kê máy chủ dành cho SYSTEM ADMIN LINUX SERVER VÕ DUY DOT COM: ########### GIỜ:09H36-NGÀY:19-02-2017 ###########

        Xung nhịp CPU đang dùng là: ~0.14%      Lượng RAM đang dùng là: ~3682MB         Tốc độ tải IO ổ cứng đang là:   ~1MB/s ĐỌC
                                                                                                                        ~0MB/s GHI
        Tổng SỐ TRUY VẤN vào port 80 là: 37     (Do tất cả 14 IP Address truy vấn đến)
        Tổng SỐ TRUY VẤN vào port 443 là: 0     (Do tất cả 1 IP Address truy vấn đến)

         Số truy vấn ĐÃ ĐƯỢC THIẾT LẬP là:                      |       TỐC ĐỘ MẠNG:
         Port 80: 1 kết nối                                     |       Đang nhận vào là: 69KB/s
         Port 443: 0 kết nối                                    |       Đang truyền đi là: 80KB/s

Những IP Address kết nối nhiều nhất đến:
     58 112.8.43.10 www.voduy.com
      6 66.249.82.96 google-proxy-66-249-82-96.google.com
      6 66.249.82.127 google-proxy-66-249-82-127.google.com
      6 171.246.203.135
      5 66.249.82.125 google-proxy-66-249-82-125.google.com
      4 123.30.175.174 bot21.coccoc.com
      2 123.30.175.212 bot42.coccoc.com
      1 94.100.181.37 picker1.i.mail.ru
      1 66.249.79.94 crawl-66-249-79-94.googlebot.com
      1 66.249.79.76 crawl-66-249-79-76.googlebot.com
      1 66.249.79.171 crawl-66-249-79-171.googlebot.com
      1 46.229.168.75
      1 46.229.168.73
      1 222.254.217.10 static.vnpt.vn
      1 183.80.227.160
      1 157.55.39.82 msnbot-157-55-39-82.search.msn.com
      1 123.30.175.181 bot28.coccoc.com

Cám ơn bạn đã sử dụng!

```
3. More Config:
---------------
Document: http://vddos.voduy.com

```
Still in beta, use at your own risk! It is provided without any warranty!
```
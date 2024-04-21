﻿# read_text_from_camera
Code Python đọc văn bản tiếng Việt từ video camera và chuyển thành giọng nói
## Cài đặt bằng terminal Ubuntu
```git clone https://github.com/brianhuster/read_text_from_camera/```

```cd read_text_from_camera```

```
sudo apt-get update
sudo apt-get install espeak
sudo apt-get install libgirepository1.0-dev
sudo apt-get install libcairo2-dev
sudo apt-get install -y libgl1-mesa-glx
sudo apt-get install tesseract-ocr-vie
sudo apt-get install -y portaudio19-dev python3-pyaudio
```

```pip install -r requirements.txt```

### Chạy chương trình
```python3 main.py```

Người dùng ra lệnh, sau đó chương trình sẽ nghe chuyển giọng nói người dùng thành văn bản qua dịch vụ của Google và hiển thị câu lệnh trên Terminal. 

Nếu câu lệnh của người dùng chứa từ "đọc chữ" thì chương trình sẽ chụp hình từ camera rồi chuyển chữ thành văn bản trên terminal, rồi đọc to văn bản qua dịch vụ chuyển văn bản thành giọng nói của Google
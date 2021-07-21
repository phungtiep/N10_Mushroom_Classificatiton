# N10_Mushroom_Classificatiton
Mushroom_classification data mining of Group 10 in Thuy Loi University Southern Campus in Viet Nam

# Chạy với tệp Mushroom_Classificatiton.ipynb

HƯỚNG DẪN SỬ DỤNG GOOGLE COLAB ĐỂ CHẠY THUẬT TOÁN
Bước 1: git clone https://github.com/phungtiep/N10_Mushroom_Classificatiton.git
Bước 2: Vào Google Drive và upload thư mục N10_Mushroom_Classificatiton vừa clone.
Bước 3: Vào thư mục N10_Mushroom_Classificatiton, sau đó click vào Mushroom_Classification.ipynb, kéo xuống thay dòng 
df = pd.read_csv('/content/drive/MyDrive/Mushroom_Classification/source_code/data/mushrooms.csv')
với 
df = pd.read_csv('/content/drive/MyDrive/N10_Mushroom_Classificatiton/N10_mushroom_classification/data/mushrooms.csv')
Bước 4: nhấn vào nút connect để két nối runtime python3
![image](https://user-images.githubusercontent.com/43229272/126512749-f5a23100-4442-40a9-954e-d7abee7f9895.png)
Bước 5: Nhấn vào Nút Play để tiến hành xác thực OAuth2 chọn tài khoản google vừa tạo foldel, tiến hành đăng nhập, sau đó copy authorization_code, paste vào ô hiển thị bên dưới.
![image](https://user-images.githubusercontent.com/43229272/126512857-67350255-a4bc-4bcb-88ed-62cbe175ed3e.png)
![image](https://user-images.githubusercontent.com/43229272/126513014-893a2983-b063-4b73-8ace-11f1258baa2d.png)
![image](https://user-images.githubusercontent.com/43229272/126513044-d3cf710b-dbb1-4872-ab46-0e6efa3f1986.png)
Sau khi paste xong nhấn enter để xác thực.
Sau đó nhấn nút play từ trên xuống dưới để thưc thi chương trình.

# Chạy với tệp Mushroom_Classificatiton.py

Bước 1: git clone https://github.com/phungtiep/N10_Mushroom_Classificatiton.git
Bước 2: cd N10_Mushroom_Classificatiton
Bước 3: Mở folder N10_mushroom_classification với Pycharm, cài đặt các thư viện cần thiết bằng cách tạo môi trường ảo mới, rê chuột vào từng dòng đầu file mushroom_classification.py để cài đặt thư viện sau kéo xuống thay dòng 
df = pd.read_csv('/content/drive/MyDrive/Mushroom_Classification/source_code/data/mushrooms.csv')
với 
df = pd.read_csv('./data/mushrooms.csv')
Bước 4: nhấn vào Tab Terminal gõ: python3 mushroom_classification.py
___THE END___

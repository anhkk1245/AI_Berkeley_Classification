# AI_Berkeley_Classification
### 1.  Perceptron
Ta cần xác định score của từng label sau đó lấy ra từ mảng score giá trị có label tốt nhất. Nếu giá trị đó chưa đúng, thì điều chỉnh weight.
### 2. Perceptron Analysis
### 3. MIRA
Khi duyệt từng giá trị C trong Cgrid ta sẽ duyệt mảng trainingData giống câu 1 để điều chỉnh weight. Sau khi tìm được giá trị C tốt nhất, dựa vào giá trị C để xác định weight.
### 4. Digit Feature Design

### 5. Behavioral Cloning
Dùng hàm classify để tìm ra action nhiều điểm nhất. Nếu giá trị dự đoán này chưa đúng thì điều chỉnh weight.
### 6. Pacman Feature Design
Dựa vào thông tin thức ăn gần nhất, và ma gần nhất để xác định 2 giá trị của features là features["closest food"] và features["closest ghost"]. 

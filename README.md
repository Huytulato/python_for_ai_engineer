# Python for AI Engineer / AI Researcher

Lộ trình học Python từ con số 0, đi theo hướng trở thành **AI Engineer / AI Researcher**, học qua các file Jupyter Notebook, dạy theo từng bài một.

## Cách học

- Mỗi bài là một file `.ipynb` trong thư mục module tương ứng.
- Học lần lượt theo thứ tự, không nhảy cóc — kiến thức sau dựa trên kiến thức trước.
- Mỗi notebook có: lý thuyết ngắn + ví dụ chạy được + bài tập thực hành + (gợi ý/lời giải ở cuối, chỉ xem sau khi tự làm).
- Làm xong bài tập trong notebook rồi mới báo để mở bài tiếp theo.

## Cài đặt môi trường (chỉ cần làm 1 lần)

Đã tạo sẵn virtual environment `.venv` và cài các thư viện cần dùng cho cả khoá học (jupyterlab, numpy, pandas, matplotlib, seaborn, scikit-learn).

Mở notebook bằng 1 trong 2 cách:

**Cách 1 — VS Code:**
1. Mở thư mục `python_for_ai_engineer` trong VS Code.
2. Cài extension "Jupyter" (Microsoft) nếu chưa có.
3. Mở file `.ipynb` của bài học, chọn kernel **"Python for AI Engineer"** ở góc trên phải.

**Cách 2 — JupyterLab trên terminal:**
```powershell
.venv\Scripts\activate
jupyter lab
```
rồi mở file notebook trong tab trình duyệt hiện ra.

## Lộ trình tổng quan (sẽ cập nhật dần)

### Module 1 — Python cơ bản (Core Python)
- [x] Bài 1: Biến, kiểu dữ liệu & toán tử
- [x] Bài 2: Chuỗi (string) và xử lý văn bản
- [x] Bài 3: Cấu trúc điều khiển (if/else, vòng lặp for/while)
- [x] Bài 4: List & Tuple
- [x] Bài 5: Dictionary & Set
- [x] Bài 6: Hàm (function), phạm vi biến, *args/**kwargs
- [x] Bài 7: Comprehension, generator, lambda
- [ ] Bài 8: Lập trình hướng đối tượng (OOP) ← **bắt đầu ở đây**
- [ ] Bài 9: Xử lý lỗi (exception) & làm việc với file
- [ ] Bài 10: Module, package, pip, virtual environment

### Module 2 — Python trung cấp cho Data/AI
- [ ] Decorator, iterator/generator nâng cao
- [ ] Làm việc với JSON/CSV, pathlib
- [ ] Type hints, viết code sạch (clean code)
- [ ] Kiểm thử cơ bản với pytest

### Module 3 — Thư viện khoa học dữ liệu
- [ ] NumPy: array, broadcasting, vectorization
- [ ] Pandas: Series, DataFrame, lọc/biến đổi dữ liệu
- [ ] Pandas nâng cao: groupby, merge, xử lý missing data
- [ ] Trực quan hoá: Matplotlib & Seaborn

### Module 4 — Toán cho AI (học qua code)
- [ ] Đại số tuyến tính với NumPy (vector, ma trận, eigenvalue)
- [ ] Xác suất thống kê cơ bản
- [ ] Giải tích & gradient (nền cho optimization/backprop)

### Module 5 — Machine Learning cơ bản
- [ ] Scikit-learn: quy trình ML, train/test split
- [ ] Linear Regression, Logistic Regression
- [ ] Decision Tree, Random Forest
- [ ] Đánh giá mô hình: metrics, cross-validation
- [ ] Feature engineering, pipeline

### Module 6 — Deep Learning
- [ ] PyTorch: tensor, autograd
- [ ] Xây neural network từ đầu bằng NumPy (hiểu bản chất)
- [ ] PyTorch: Dataset, DataLoader, training loop
- [ ] CNN cơ bản
- [ ] RNN/LSTM cơ bản
- [ ] Attention & Transformer cơ bản

### Module 7 — AI Engineering hiện đại
- [ ] Gọi API LLM (OpenAI/Anthropic), prompt engineering
- [ ] Embeddings & vector search
- [ ] RAG (Retrieval-Augmented Generation) cơ bản
- [ ] Fine-tuning cơ bản / LoRA
- [ ] Agent & tool use cơ bản

### Module 8 — Kỹ năng Research & MLOps
- [ ] Đọc paper, viết báo cáo thí nghiệm
- [ ] Reproducibility, logging (wandb/mlflow)
- [ ] Deploy model cơ bản (FastAPI)

> Lộ trình có thể điều chỉnh theo tiến độ và nhu cầu thực tế trong quá trình học.

## Tiến độ hiện tại

**Đang học:** Module 1 — Bài 8: Lập trình hướng đối tượng (`module_01_python_co_ban/08_oop.ipynb`)

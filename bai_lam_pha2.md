# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 04
- **Họ tên:** Nguyễn Trần Đan Linh
- **Lớp:** CNTT1
- **Link repository Pha2:** https://github.com/HCM-K26-CNTT1/K26-HCM-CNTT1_PromptAI_H02_Pha1.git
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé xe ra JSON

**KET QUA AI**

```text
[
  {
    "ma_tuyen": "SGDL",
    "ngay_di": "2026-12-22",
    "ve_nguoi_lon": 2,
    "ve_tre_em": 1,
    "loai_cho": "giuong",
    "ghi_chu": null
  },
  {
    "ma_tuyen": "SGNT",
    "ngay_di": "2027-01-02",
    "ve_nguoi_lon": 3,
    "ve_tre_em": 0,
    "loai_cho": null,
    "ghi_chu": "một người đang mang thai 6 tháng"
  },
  {
    "ma_tuyen": "SGCT",
    "ngay_di": null,
    "ve_nguoi_lon": 4,
    "ve_tre_em": 0,
    "loai_cho": "ghe",
    "ghi_chu": "bà nội đi xe lăn"
  }
]
```

**Link trò chuyện:** https://chatgpt.com/share/6b078e9c-43a0-83ec-a61a-1f10d1778a9e

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Bước 1: Tiền vé người lớn

8 × 320.000 = 2.560.000 đồng

Bước 2: Tiền vé trẻ em
- Trẻ 6 tuổi: 320.000 × 75% = 240.000 đồng
- Trẻ 7 tuổi: 320.000 × 75% = 240.000 đồng
- Trẻ 9 tuổi: 320.000 × 75% = 240.000 đồng
- Bé 2 tuổi: Miễn phí = 0 đồng
Tổng tiền vé trẻ em: 240.000 × 3 + 0 = 720.000 đồng

Bước 3: Tổng tiền vé trước giảm giá

2.560.000 + 720.000 = 3.280.000 đồng

Bước 4: Tiền giảm giá đoàn

3.280.000 × 5% = 164.000 đồng

Bước 5: Tiền phụ thu hành lý cồng kềnh

2 × 100.000 = 200.000 đồng

Bước 6: Tổng tiền thanh toán

(3.280.000 − 164.000) + 200.000 = 3.316.000 đồng

[Result: 3.316.000 đồng]
```

**Link trò chuyện:** https://chatgpt.com/share/6b078f35-7cc0-83ec-a83f-44a1f7c4dfae

### b) Kiểm tra kết quả AI

Kết quả của AI là đúng.

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_loai_xe",
  "so_khach": 3,
  "so_chang_bi_doi": 2,
  "tom_tat": "Cả hai chặng đi và về đều đổi từ xe giường nằm sang xe ghế ngồi."
}
```

**Link trò chuyện:** https://chatgpt.com/share/6b078fcd-21b4-83ec-b225-45766e1c11dd

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**

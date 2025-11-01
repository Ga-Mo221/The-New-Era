# 🏰 KỶ NGUYÊN MỚI – *The New Era*
*A Real-Time Strategy Survival Game built with Unity*

![Poster](./Docs/Poster.png)

---

## 🌅 Giới thiệu

> “Từ đống tro tàn, con người dựng lại nền văn minh của mình.  
> Khi mặt trời lặn, quái vật trỗi dậy – và chỉ có chiến lược mới cứu được chúng ta.”

**Kỷ Nguyên Mới** là trò chơi **RTS – Sinh tồn & Quản lý căn cứ**, nơi người chơi dẫn dắt những người sống sót cuối cùng tái thiết thế giới sau thảm họa hắc ám.

Ban ngày là thời khắc **xây dựng, khai thác, huấn luyện**,  
ban đêm là **cuộc chiến sinh tồn**, khi bè lũ quái vật tràn ra từ rừng sâu.

---

## 🎮 Gameplay Core Loop

1. **Khởi đầu**
   - Bắt đầu với **Castle** (thành chính) và lượng tài nguyên cơ bản.
   - Nhiệm vụ: thu thập, xây dựng, huấn luyện quân đội.

2. **Chu kỳ ngày – đêm**
   - 45 giây = 2 giờ trong game.  
   - **Ban ngày:** xây dựng & mở rộng.  
   - **Ban đêm:** quái vật tấn công theo từng **Wave**.

3. **Auto Train Mode**
   - Kích hoạt để AI tự điều khiển lính.
   - Người chơi chỉ tập trung vào chiến lược & quản lý tài nguyên.

4. **Tăng trưởng**
   - Mỗi ngày → quái vật mạnh hơn.  
   - Mục tiêu cuối: **phá hủy Enemy Castle trước khi bị áp đảo.**

---

## ⚔️ Các đơn vị (Units)

| Class | Vai trò | Đặc điểm | Có thể thu thập |
|-------|----------|-----------|----------------|
| **Warrior** | Tank – cận chiến | Máu cao, tấn công ổn định | ✅ |
| **Archer** | DPS – tầm xa | Bắn xuyên sau X phát | ✅ |
| **Lancer** | Damage chủ lực | Sát thương cao, tầm trung | ✅ |
| **Healer** | Support | Hồi máu, buff nhóm | ❌ |
| **TNT** | Kamikaze | Nổ khi chết, sát thương AOE | ❌ |

---

## 🏗️ Công trình (Buildings)

| Tên | Vai trò | Ghi chú |
|-----|----------|---------|
| **Castle** | Trung tâm căn cứ | Nâng cấp mở lính mới |
| **Storage** | Nhà kho tài nguyên | Lính ưu tiên nộp gần nhất |
| **Tower** | Phòng thủ | Chỉ hoạt động khi có Archer |

---

## 🐻 Sinh vật & Kẻ thù

| Loại | Hành vi | Drop |
|------|----------|------|
| **Gấu** | Trung lập, tấn công khi bị phát hiện | Thịt |
| **Cừu** | Nhát, bỏ chạy | Thịt |
| **Nhện / Rắn** | Tấn công chủ động | Thịt |
| **Orc** | Máu trâu, sát thương thấp | – |
| **Minotaur (Boss)** | Đòn đánh rộng, máu cực trâu | – |
| **Shaman (Boss)** | Tầm xa, phép AOE | – |

---

## 🔮 Spell (Phép thuật)

| Tên | Tác dụng |
|------|-----------|
| **Healing Aura** | Hồi máu khu vực |
| **Berserk** | Tăng máu và sát thương |
| **Farm Boost** | Tăng tốc độ khai thác tài nguyên |

---

## 🧠 Hệ thống AI

- **AI thu thập:** Ưu tiên nguồn gần nhất → nộp vào kho gần nhất.  
- **AI chiến đấu:** Phát hiện trong bán kính → tấn công.  
- **AI hồi máu:** Healer chọn đồng minh yếu nhất.  
- **AI enemy:** Tuần tra quanh trại, phát động tấn công khi phát hiện người chơi.

---

## 🕹️ Công nghệ sử dụng

| Công cụ | Vai trò |
|----------|----------|
| 🧱 **Unity** | Engine chính |
| 🎨 **Photoshop / Aseprite** | Thiết kế pixel-art |
| 💻 **Visual Studio Code** | Lập trình C# |
| 🧠 **ChatGPT API** | Hỗ trợ mô phỏng đối thoại / NPC |
| 🗂️ **Trello / Notion** | Quản lý tiến độ |
| 🧾 **Git & GitHub** | Quản lý version |

---

## 🧩 Cài đặt & Chạy thử

```bash
# Clone project
git clone https://github.com/<your-username>/KyNguyenMoi.git
cd KyNguyenMoi

# Mở bằng Unity (phiên bản 2022.3+)

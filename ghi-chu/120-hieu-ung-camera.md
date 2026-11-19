# 120 hiệu ứng chuyển động camera (Google Flow / Kling / Wan)

Nguồn: NBOX AI — `Google_Flow_120_hieu_ung_camera.pptx`
([thư mục Drive](https://drive.google.com/drive/folders/1bgnjOj5fHbfnaGsDUK7ozsYHx0xBOsNf))

## Cách dùng trong 4 bước

1. **Mở Google Flow** — chọn *Image to Video* với ảnh của bạn, hoặc *Text to Video*.
2. **Thêm từ khoá** — gõ cụm lệnh tiếng Anh vào cuối prompt mô tả cảnh.
3. **Chỉ 1–2 chuyển động** — mỗi lần kết hợp tối đa hai chuyển động để kết quả ổn định.
4. **Tăng chất điện ảnh** — thêm tốc độ (`slow`, `fast`, `smooth`) và ánh sáng (`golden hour`…).

Ví dụ prompt:

```
a woman leaning on a blue boat, orbit 360, golden hour light
```

> Kết quả có thể khác nhau tuỳ ảnh và phiên bản model — thử vài lần để chọn bản đẹp nhất.

---

## A. Xoay & bay quanh chủ thể (01–12)

Đưa người xem đi vòng quanh chủ thể, hoàn hảo để giới thiệu nhân vật hay sản phẩm.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 01 | `orbit 360` | Camera xoay trọn một vòng quanh chủ thể |
| 02 | `orbit left` | Xoay vòng sang trái quanh chủ thể |
| 03 | `orbit right` | Xoay vòng sang phải quanh chủ thể |
| 04 | `half orbit` | Xoay nửa vòng 180 độ |
| 05 | `slow orbit` | Xoay chậm, sang trọng |
| 06 | `fast orbit` | Xoay nhanh, kịch tính |
| 07 | `arc shot` | Lượn cung tròn nhẹ quanh chủ thể |
| 08 | `orbit and rise` | Vừa xoay vừa nâng lên cao |
| 09 | `orbit and descend` | Vừa xoay vừa hạ xuống |
| 10 | `spiral up` | Bay xoắn ốc lên trời |
| 11 | `spiral down` | Bay xoắn ốc từ trên xuống |
| 12 | `360 turntable` | Chủ thể như đặt trên bàn xoay, camera đứng yên |

## B. Drone & góc cao (13–24)

Góc nhìn trên cao, bay lượn tự do như flycam.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 13 | `drone fly` | Camera bay như flycam |
| 14 | `drone fly over` | Bay lướt qua phía trên chủ thể |
| 15 | `drone fly through` | Bay xuyên qua khung cửa, hành lang, tán cây |
| 16 | `drone reveal` | Bay lên để lộ toàn cảnh phía sau |
| 17 | `drone pull back` | Bay lùi ra xa, mở rộng khung hình |
| 18 | `drone push in` | Bay tiến thẳng vào chủ thể |
| 19 | `aerial view` | Góc nhìn trên không |
| 20 | `top down shot` | Nhìn thẳng từ trên xuống (bird's eye) |
| 21 | `top down rotate` | Nhìn từ trên xuống và xoay tròn |
| 22 | `FPV drone` | Flycam FPV tốc độ cao, lượn sát |
| 23 | `FPV dive` | FPV lao thẳng xuống |
| 24 | `flyover landscape` | Bay lướt qua cảnh quan rộng |

## C. Tiến – lùi – trượt (25–38)

Dolly, push, pull: nhịp kể chuyện cơ bản của máy quay.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 25 | `dolly in` | Máy quay tiến lại gần chủ thể |
| 26 | `dolly out` | Máy quay lùi ra xa |
| 27 | `push in` | Đẩy máy chậm vào mặt nhân vật |
| 28 | `pull out` | Kéo máy ra để lộ bối cảnh |
| 29 | `slow push in` | Đẩy vào thật chậm, tạo cảm xúc |
| 30 | `fast push in` | Đẩy vào nhanh, gây bất ngờ |
| 31 | `dolly zoom` | Hiệu ứng Vertigo: tiến máy + zoom ngược |
| 32 | `reverse dolly zoom` | Dolly zoom chiều ngược lại |
| 33 | `truck left` | Máy trượt ngang sang trái |
| 34 | `truck right` | Máy trượt ngang sang phải |
| 35 | `tracking shot` | Máy bám theo chủ thể đang di chuyển |
| 36 | `follow shot` | Đi theo sau lưng nhân vật |
| 37 | `lead shot` | Đi lùi phía trước nhân vật |
| 38 | `parallax slide` | Trượt ngang tạo chiều sâu tiền cảnh – hậu cảnh |

## D. Lia – ngước – nghiêng (39–50)

Pan, tilt, roll: dẫn ánh nhìn người xem theo ý bạn.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 39 | `pan left` | Lia máy sang trái |
| 40 | `pan right` | Lia máy sang phải |
| 41 | `slow pan` | Lia chậm toàn cảnh |
| 42 | `whip pan` | Lia cực nhanh, nhoè chuyển cảnh |
| 43 | `tilt up` | Camera ngước lên |
| 44 | `tilt down` | Camera cúi xuống |
| 45 | `tilt up reveal` | Ngước lên để lộ toà nhà, bầu trời |
| 46 | `dutch angle` | Nghiêng khung hình tạo căng thẳng |
| 47 | `camera roll` | Xoay tròn quanh trục ống kính |
| 48 | `barrel roll` | Lộn vòng 360 độ như phim hành động |
| 49 | `pan and tilt` | Vừa lia vừa ngước theo chủ thể |
| 50 | `swing shot` | Đung đưa nhẹ như con lắc |

## E. Nâng – hạ – cẩu (51–58)

Pedestal, crane, jib: nâng hạ máy quay để mở ra không gian.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 51 | `pedestal up` | Nâng thẳng camera lên cao |
| 52 | `pedestal down` | Hạ thẳng camera xuống thấp |
| 53 | `crane up` | Cần cẩu nâng máy lên, mở toàn cảnh |
| 54 | `crane down` | Cần cẩu hạ máy xuống chủ thể |
| 55 | `jib shot` | Máy lướt cung trên cần jib |
| 56 | `boom shot` | Cẩu máy lên cao lướt qua đám đông |
| 57 | `rise and reveal` | Nâng lên lộ cảnh phía sau vật cản |
| 58 | `ground to sky` | Từ mặt đất vút lên bầu trời |

## F. Zoom & ống kính (59–72)

Thay đổi tiêu cự và chất ống kính cho từng khung hình.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 59 | `zoom in` | Phóng to vào chủ thể |
| 60 | `zoom out` | Thu nhỏ ra xa |
| 61 | `crash zoom` | Zoom giật cực nhanh vào mặt |
| 62 | `snap zoom` | Zoom bật nhanh kiểu hài hước |
| 63 | `slow zoom` | Zoom chậm, cảm giác hồi hộp |
| 64 | `earth zoom out` | Zoom ra tận ngoài Trái Đất |
| 65 | `earth zoom in` | Từ vũ trụ zoom vào tận chủ thể |
| 66 | `macro zoom` | Zoom cận cảnh chi tiết siêu nhỏ |
| 67 | `eye zoom` | Zoom xuyên vào trong mắt nhân vật |
| 68 | `fisheye lens` | Ống mắt cá, méo cong rộng |
| 69 | `wide angle` | Góc siêu rộng |
| 70 | `telephoto compression` | Ống tele nén hậu cảnh |
| 71 | `anamorphic lens` | Ống anamorphic, vệt sáng ngang điện ảnh |
| 72 | `tilt shift` | Hiệu ứng mô hình thu nhỏ |

## G. Lấy nét & độ sâu (73–80)

Điều khiển điểm nét và chiều sâu của khung hình.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 73 | `focus pull` | Chuyển nét sang chủ thể gần nhất |
| 74 | `rack focus` | Chuyển nét từ tiền cảnh ra hậu cảnh |
| 75 | `shallow depth of field` | Xoá phông mạnh |
| 76 | `deep focus` | Rõ nét toàn bộ khung hình |
| 77 | `bokeh background` | Nền bokeh lung linh |
| 78 | `focus reveal` | Từ nhoè chuyển dần sang rõ nét |
| 79 | `split diopter` | Rõ nét cả gần lẫn xa cùng lúc |
| 80 | `soft focus` | Nét mềm, mơ màng |

## H. Thời gian & tốc độ (81–90)

Bẻ cong thời gian: tua nhanh, quay chậm, đóng băng.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 81 | `time lapse` | Tua nhanh thời gian |
| 82 | `day to night time lapse` | Chuyển từ ngày sang đêm |
| 83 | `hyperlapse` | Tua nhanh khi camera đang di chuyển |
| 84 | `slow motion` | Quay chậm |
| 85 | `super slow motion` | Siêu chậm, từng giọt nước |
| 86 | `speed ramp` | Đang nhanh chuyển sang chậm đột ngột |
| 87 | `freeze frame` | Đóng băng khung hình |
| 88 | `bullet time` | Đóng băng thời gian + xoay quanh chủ thể |
| 89 | `reverse motion` | Chạy ngược thời gian |
| 90 | `motion blur` | Nhoè chuyển động tốc độ cao |

## I. Cầm tay & tự nhiên (91–98)

Chuyển động chân thật như đang quay bằng tay.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 91 | `handheld` | Cầm tay rung nhẹ, chân thật |
| 92 | `shaky cam` | Rung mạnh, hỗn loạn |
| 93 | `steadicam` | Bám theo mượt mà không rung |
| 94 | `gimbal shot` | Mượt như gimbal |
| 95 | `POV shot` | Góc nhìn thứ nhất của nhân vật |
| 96 | `walking POV` | Góc nhìn khi đang đi bộ |
| 97 | `car mount shot` | Máy gắn trên xe đang chạy |
| 98 | `camera shake impact` | Rung giật khi có va chạm |

## J. Góc máy & bố cục (99–110)

Chọn điểm đặt máy và cách sắp xếp khung hình.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 99 | `epic shot` | Chuyển động máy quay chuẩn điện ảnh |
| 100 | `establishing shot` | Cảnh toàn giới thiệu bối cảnh |
| 101 | `low angle` | Góc thấp, chủ thể trông hùng vĩ |
| 102 | `high angle` | Góc cao nhìn xuống |
| 103 | `worm's eye view` | Góc sát mặt đất nhìn lên |
| 104 | `over the shoulder` | Qua vai nhân vật |
| 105 | `extreme close up` | Cận cực sát chi tiết |
| 106 | `close up` | Cận mặt |
| 107 | `medium shot` | Trung cảnh |
| 108 | `wide shot` | Toàn cảnh |
| 109 | `symmetrical shot` | Bố cục đối xứng |
| 110 | `silhouette shot` | Bóng đen ngược sáng |

## K. Hiệu ứng đặc biệt (111–120)

Những chuyển động sáng tạo, tạo ấn tượng mạnh.

| # | Từ khoá | Ý nghĩa |
|---|---|---|
| 111 | `through the window` | Bay xuyên qua cửa sổ |
| 112 | `through the keyhole` | Xuyên qua lỗ khoá |
| 113 | `portal transition` | Chuyển cảnh qua cánh cổng |
| 114 | `match cut transition` | Chuyển cảnh khớp hình |
| 115 | `infinite zoom` | Zoom vô tận lặp lại |
| 116 | `vertigo effect` | Chóng mặt kiểu Hitchcock |
| 117 | `levitation float` | Camera lơ lửng trôi chậm |
| 118 | `underwater move` | Chuyển động dưới nước |
| 119 | `lens flare sweep` | Vệt loé sáng quét qua ống kính |
| 120 | `light leak` | Vệt sáng rò kiểu phim cũ |

---

## ★ 5 combo gợi ý

| # | Combo | Dùng cho |
|---|---|---|
| 01 | `slow push in` + `shallow depth of field` | Cảnh cảm xúc |
| 02 | `drone reveal` + `golden hour` | Cảnh mở đầu hoành tráng |
| 03 | `orbit 360` + `slow motion` | Giới thiệu sản phẩm / nhân vật |
| 04 | `time lapse` + `crane up` | Cảnh thành phố / công trình |
| 05 | `FPV dive` + `motion blur` | Cảnh hành động tốc độ |

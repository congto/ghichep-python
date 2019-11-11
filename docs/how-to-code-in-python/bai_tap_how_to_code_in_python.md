# Bài tập python theo chủ đề

## Bài tập về file

### Bài 1:
Cho file mẫu với nội dung chứa log về việc gửi nhận email theo link: `https://www.py4e.com/code3/mbox-short.txt`

Trong file này, các dòng bắt đầu với cụm từ  `X-DSPAM-Confidence:` sẽ chứa giá trị đánh giá mức độ spam.

![DSPAM](https://image.prntscr.com/image/dIlcIJtOQgysej3oqznJjg.png)

Hãy viết một chương trình cho phép lọc ra các dòng bắt đầu với chuỗi `X-DSPAM-Confidence:` ở trên theo dạng

```
X-DSPAM-Confidence: 0.8475
X-DSPAM-Confidence: 0.6178
X-DSPAM-Confidence: 0.9846
...

Sau khi hiển thị được các dòng bắt đầu là chuỗi `X-DSPAM-Confidence:`  thực hiện tác các giá trị sau dấu hai chấm để tính giá trị trung bình và in ra màn hình theo dạng dưới đây:

```
0.6528
0.7002
0.7554
0.6956
0.6959
0.7556
0.9846
0.8509
0.9907
Trung binh la:  0.7507185185185187
```



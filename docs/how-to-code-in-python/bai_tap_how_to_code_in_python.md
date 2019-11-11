# Bài tập python theo chủ đề

## Bài tập về file

### Bài 1:
Cho file mẫu với nội dung chứa log về việc gửi nhận email theo link: `https://www.py4e.com/code3/mbox-short.txt`

Trong file này, các dòng bắt đầu với cụm từ  `X-DSPAM-Confidence:` sẽ chứa giá trị của điểm số đánh giá xem mail đó có bị spam hay không.

Link: http://prntscr.com/pv8771

Hãy viết một chương trình cho phép lọc ra các dòng ``X-DSPAM-Confidence:` ở trên theo dạng

```
X-DSPAM-Confidence: 0.8475
X-DSPAM-Confidence: 0.6178
X-DSPAM-Confidence: 0.9846
...
```


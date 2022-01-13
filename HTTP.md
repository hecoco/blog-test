## HTTP





### 请求
请求动词(GET/POST) 路径加查询参数 协议名/版本号(HTTP/1.1)  
Host: 域名或IP  
Accept: text/html text/css text/javascript  
Content-Type: 请求体的格式  
回车  
请求体 一般为空  


### 响应
协议名/版本号 状态码(200/404/500) 状态字符串(OK)  
Content-Type: 响应体格式  
回车  
响应体  


### curl
curl -v http://127.0.0.1:8888  
设置请求动词    -X POST  
设置请求头      -H 'Name: value'  
设置请求体      -d '内容'  

读取请求动词    request.method  
读取路径        request.url 路径，带查询参数  
                request.path 纯路径，不带查询参数  
                request.query 只有查询参数  
读取请求头      request.headers['accept']  
读取请求体

设置响应状态码  response.statusCode = 200  
设置响应头      response.setHeader('Content-Type', 'text/html');  
设置响应体      response.write('内容')  
结束响应        response.end();  



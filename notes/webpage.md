# webpage

![alt text](image.png)
![alt text](image-1.png)

git add . ( add all the file now )
git commit m "what u say to notice add" , or git commit 
git push   ( push to repository github (luar biasa box ))







RESTful API 就是遵循 REST 设计原则的 API

核心是：

用 URL 表示资源

用 HTTP 方法（GET/POST/PUT/DELETE）访问资源

返回数据一般是 JSON

例如：

bash
Copy
Edit
GET https://api.openweathermap.org/data/2.5/weather?q=Kuala%20Lumpur&appid=XXXX
GET → 获取数据

weather → 资源路径

q、appid → 查询参数（城市名和 API key）


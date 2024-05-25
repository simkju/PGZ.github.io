# simkju.github.io
个人网站
# hahahhahahahah

# ueifbiwefslc
<html><body><table border='1'><tr><td>Cell 1,1</td><td>Cell 1,2</td><td>Cell 1,3</td><td>Cell 1,4</td><td>Cell 1,5</td><td>Cell 1,6</td><td>Cell 1,7</td><td>Cell 1,8</td><td>Cell 1,9</td><td>Cell 1,10</td><td>Cell 1,11</td><td>Cell 1,12</td><td>Cell 1,13</td><td>Cell 1,14</td><td>Cell 1,15</td><td>Cell 1,16</td><td>Cell 1,17</td><td>Cell 1,18</td><td>Cell 1,19</td><td>Cell 1,20</td><td>Cell 1,21</td><td>Cell 1,22</td><td>Cell 1,23</td><td>Cell 1,24</td><td>Cell 1,25</td><td>Cell 1,26</td><td>Cell 1,27</td><td>Cell 1,28</td><td>Cell 1,29</td><td>Cell 1,30</td><td>Cell 1,31</td><td>Cell 1,32</td><td>Cell 1,33</td><td>Cell 1,34</td><td>Cell 1,35</td><td>Cell 1,36</td><td>Cell 1,37</td><td>Cell 1,38</td><td>Cell 1,39</td><td>Cell 1,40</td><td>Cell 1,41</td><td>Cell 1,42</td><td>Cell 1,43</td><td>Cell 1,44</td><td>Cell 1,45</td><td>Cell 1,46</td><td>Cell 98,43</td><td>Cell 98,44</td><td>Cell 98,45</td><td>Cell 98,46</td><td>Cell 98,47</td><td>Cell 98,48</td><td>Cell 2,7</td><td>Cell 100,50</td></tr></table></body></html>

<body>
    <h1>您的IP地址是：</h1>
    <p id="ip-address"></p >

    <script>
        // 定义要使用的API URL
        const apiUrl = 'https://api.ipify.org?format=json';

        // 发送请求到API
        fetch(apiUrl)
            .then(response => response.json()) // 解析响应为JSON
            .then(data => {
                // 获取IP地址并显示在页面上
                const ipAddressElement = document.getElementById('ip-address');
                ipAddressElement.textContent = data.ip;
            })
            .catch(error => {
                console.error('获取IP地址时出错：', error);
            });
    </script>
</body>

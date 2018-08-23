<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <form action="https://stevenchen7500.github.io/homework/" method="POST">
        <div class="username">
            <label for="username">姓名:</label>
            <input type="text" name="username" id="username" placeholder="用户名">
        </div>
        <div class="password">
            <label for="password">密码:</label>`
            <input type="password" name="password" id="password" value="12345678">
        </div>
    <div class="sex">
        <label for="">性别：</label>
        <input type="radio" name="sex" value="male"  checked="true">男
        <input type="radio" name="sex"  value="female"><label for="sex">女</label>        
    </div>
    <div class="sexy">
        <label for="">取向：</label>
            <input type="radio" name="sexy" value="love male" >男 
            <input type="radio" name="sexy"  value="love female"  checked="true">女      
    </div>
    <div class="hobby">
        <label for="">爱好:</label>
        <input type="checkbox" name="hobby" value="dota">dota
        <input type="checkbox" name="hobby" value="tarvel"checked>旅游
        <input type="checkbox" name="hobby" value="pet" checked>宠物
    </div>
    <div class="textarea">
        <label >评论:</label>
        <textarea name="textarea"  cols="30" rows="10">ddd</textarea>
    </div>
    <div class="selected">
        <label >我的car:</label>
        <select name="car" id="">
            <option value="萨博">萨博</option>
            <option value="大众">大众</option>
            <option value="奔驰">奔驰</option>
        </select>
    </div>
    <button>提交</button>
    </form>
</body>
</html>

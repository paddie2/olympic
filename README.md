# olympic
<!DOCTYPE html> 
<html>
    <head lang="en">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <link rel="stylesheet" href="../css/test1.css">
        <title> 增删改查</title>
    </head>
    <body>
        <from action="">
            <fieldset>
                <legend>添加</legend>
                名称:<input type="text" name="breed"><br>
                简介:<input type="text" name="desc"><br>
                <select name="" size="1">
                    <option value="">中华田园猫</option>
                    <option value="">美国</option>
                    <option value="">英国</option>
                    <option value="">俄罗斯</option>
                </select>
                <h4>性格特点:</h4>
                <textarea  name="areaName"rows="10" cols="30">
                    
                </textarea>
                <h4>优点:</h4>
                <textarea  name="areaName"rows="10" cols="30">
                    
                </textarea><br>
                图片:<input type="img">
                <br>
                是否有斑纹:
                <input type="radio" name="breed">是
                <input type="radio" name="breed" >否
                <br><br>
                主要颜色组成:
                <input type="checkbox" name="color">橙色
                <input type="checkbox" name="color">黑色
                <input type="checkbox" name="color">金色
                <input type="checkbox" name="color">银色
                <br><br>
                <input type="submit">
                <input type="reset" name="reset" value="重置">
            </fieldset>   
        </from>
    </body>
    </html>

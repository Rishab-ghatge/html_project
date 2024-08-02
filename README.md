<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project</title>
</head>
<body>
    <header><big>This is my important Project</big></header>
    <hr>

    <main>
        <p>This is my ordered list of languages i know</p>
        <ol type="A">
            <li>html</li>
            <li>css</li>
            <li>java</li>
            <li>javascript</li>
            <li>c++</li>
        </ol>
        <hr>

        <p>This is my unordered list of languages i know</p>
        <ul>
            <li>html</li>
            <li>css</li>
            <li>java</li>
            <li>javascript</li>
            <li>c++</li>
        </ul>
        <hr>

        <p>now I am going to make a table </p>

        <table border="2">
            <caption>all student information</caption>
            <tr>
                <th colspan="3">chirkut details are given below</th>
            </tr>
            
            <tr>
                <th>name</th>
                <th>age</th>
                <th>phone number</th>
                <th>email</th>
            </tr>
            <tr>
                <td>chirkut 1</td>
                <td>20</td>
                <td>9810896447</td>
                <td>chirkut 1 @gmail.com</td>
            </tr>
            <tr>
                <td>chirkut 2</td>
                <td>20</td>
                <td>9990098064</td>
                <td>chirkut 2 @gmail.com</td>

            </tr>

        </table>
        <hr>
        <form action="/contact-me.php" method="post"> 
        <p>now I am going to make a form to contact me </p>
        
        <label for="username">username</label>
        <input type="text" id="username" placeholder="enter your name" recquired="true"><br>

        <label for="password">password</label>
        <input type="password" id="password" placeholder="enter password" required="true"><br>

        <label for="email">email id</label>
        <input type="email" id="email " ><br>

        <label for="contact">contact number</label>
        <input type="number" id="contact"><br>

        <p>please specify your gender also</p>

        <label for="male">male</label>
        <input type="radio" id="male" name="gender" value="male"><br>

        <label for="female">female</label>
        <input type="radio" id="female" name="gender" value="female"><br>

        <label for="other">other</label>
        <input type="radio" id="other" name="gender" value="other"><br>

        <p>enter the reason for contacting me </p><br>
        <label for="place bulk order"> place bulk order</label>
        <input type="checkbox" id="place bulk order" name="reason" value="place bulk order"><br>
        
        <label for="place small order"> place small order</label>
        <input type="checkbox" id="place small order" name="reason" value="place small order"><br>
        
        <label for="single quantity"> single quantity</label>
        <input type="checkbox" id="single quantity"  name="reason" value="single quantity"><br>
        
        <label for="other purpose"> other purpose</label>
        <input type="checkbox" id="other purpose" name="reason" value="other purpose"><br>

        <p>enter the country you belong to </p>
        <select name="coutnry" id="coutnry">
            <option value="india">india</option>
            <option value="canada"> canada</option>
            <option value="usa">usa</option>
            <option value="japan">japan</option>
            <option value="korea">korea</option>
            <option value="uttrakhand">uttrakhand</option>
        </select><br>

        <p>if you have any other query please describe here </p><br>
        <textarea rows="5" cols="50">
            enter here
        </textarea>
        <br>

        <input type="submit" value="submit">
        </form>
        <hr>
        <br>


        
        <iframe src="https://www.youtube.com/embed/rklidcZ-aLU?si=JRNRKNnc4hxecrR2" width="400" height="200"></iframe> <br>

        <p><big> Thanks </big></p>








    </main>
</body>
</html>

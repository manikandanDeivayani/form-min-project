# form-min-project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: white;
            margin: 0;
            padding: 16px;
        }
        
        .social-icon{
            padding-top: 16px;
            padding-bottom: 16px;
            padding-left: 32px;
            padding-right: 32px;
        }
        form{
            
            background-color: white;
            width: 700px;
            text-align: center;
            margin-left: auto;
            margin-right: auto;
            border: 1px solid #ccc;
        }
        #form-heading{
            font-size: 32px;
            padding-top: 56px;
            padding-bottom: 32px;
        }
        #social-wrapper{
            background-color: #a6dcec;
        }
        .input-item{
            font-size: 18px;
            padding-bottom: 12px;
            margin-bottom: 25px;
            border: 0;
            border-bottom: 1px solid #ccc;
            width: 100%;
        }
        #input-wrapper{
            padding: 80px 80px 40px 80px;
        }

        #submit-button{
            background-color: blue;
            padding: 12px 24px 12px 24px;
            font-size: 18px;
            color: white;
            border: none;
        }
    </style>
</head>
<body style="background-color: rgb(139, 163, 172);">
    <form>
            <h1 id="form-heading">Register</h1>
            <div id="social-wrapper">
                <img class="social-icon" src="data:image/png;base64,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" alt="google" height="50px" width="50px">
                <img class="social-icon" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Facebook_logo_%28square%29.png/240px-Facebook_logo_%28square%29.png" alt="facebook" height="50px" width="50px">
                <img class="social-icon" src="data:image/png;base64,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" alt="gitup" height="50px" width=50px">
                <img class="social-icon" src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="linkedin" height="50px" width="50px">
            </div>
            <div id="input-wrapper">
                <div>
                    <input class="input-item" type="text" name="Username" placeholder="Username">
                </div>
                <div >
                    <input class="input-item" type="email" placeholder="Email">
                </div>
                <div >
                    <input class="input-item" type="password" placeholder="Password">
                </div>
                <div >
                    <input class="input-item" type="password" placeholder="Confirm password">
                </div>
                <input id="submit-button" type="submit" value="Register">
            </div>
                    
            
    </form>
</body>
</html

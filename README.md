-<!DOCTYPE html>
<html lang="en">
 <link
   id="favicon"
    rel="icon"
    href="https://cdn.discordapp.com/attachments/810773787892252724/810776760957796393/unknown.png"
    type="image/x-icon"
  />
<head>
  
    <meta charset="UTF-8">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
    <link href="https://fonts.googleapis.com/css?family=Lato&display=swap" rel="stylesheet">
    <script src="./JS/index.js"></script>
    <title>Fake PayPal Generator</title>
</head>
  
<style>
    * {
        font-family: 'Lato';
        font-size: 18px;
        outline: none;
        outline-color: white;
        overflow: hidden auto;
    }
    
    html,
    body {
        width: 100%;
        height: 100%;
    }
    
    img {

        padding-bottom: 20px;
        margin-left: 5%;
    }
</style>

<body style="color: white;" class="bg-dark">

    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/PayPal_logo.svg/800px-PayPal_logo.svg.png" alt="paypal Wallpaper">

    <br>

    <div class="container">

        <div class="firmware">
            <div class="form-group">
                <div class="row ml-0">
                    <div class="col-xs-6">

                        <input type="text" id="price" required class="form-control " placeholder="00.00">
                    </div>
                    <div class="col-xs-6 ml-2">

                        <select class="form-control " id="category">
                    <option value="eur">EUR</option>
                    <option value="usd">USD</option>
                    <option value="gpb">GPB</option>
                  </select>
                    </div>
                </div>
            </div>
            <input type="email" id="email" required class="form-control " placeholder="example@service.com">
            <br><br>
            <button type="button" onclick="paypalProofGen()" class="btn btn-primary">Generate</button>
            <br><br>
        </div>
    </div>


</html> 👋 Hi, I’m @thijsxa
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
thijsxa/thijsxa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

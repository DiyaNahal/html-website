<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>the website</title>
    <style>
        header {
            border: 2px solid black;
            height: 90px;
        }
        

        .navbar {
            text-decoration: none;
        }

        .subnav {
            border: .2px solid black;
            margin-top: 5px;
            margin-bottom: 10px;
            padding: 5px;
            height: 35px;
            font-weight: bold;
            background-color: rgb(250, 223, 223);
        }

        .subnav a {
            text-decoration: none;
            margin-left: 50px;
            color: black;
        }

        .subnav a:hover {
            background-color:rgb(140, 140, 248);
        }

        .password {
            display: flex;
            align-items: x;
            margin-left: 100px;
            padding: 10px;

        }

        .nav {
            display: flex;
            align-items: x;
            border: 1.5px solid black;

            margin: 5px;
            background-color: rgb(197, 44, 44);
            font-size: 30px;
            padding: 5px;

        }

        .container {
            display: flex;


        }

        .container1 {
            /* border: 2px solid; */
            height: 330px;
            width: 700px;
            padding: 10px;
            background-color: rgb(195, 195, 242);
        }

        .container2 {
            /* border: 2px solid black; */
            height: 350px;
            width: 1000px;
            margin-left: 20px;
            border-top: 1.5px solid black;
            border-right: 1.5px solid black;
        }

        .container3 {
            /* border: .5px solid black; */
            height: 150px;
            width: 100%;
            margin-top: 15px;
            background-color: rgb(241, 251, 251);

        }

        .container4 {
            /* border: 2px solid black; */
            height: 100px;
            width: 1375px;
            margin-top: 15px;
        }

        .feedback {
            /* border: 2px solid black; */
            width: 100%;
            height: 90px;
        }

        .searchbutton {
            margin-left: 330px;
            width: 100%;
        }

        input[type="text"] {
            width: 90%;
            border-color: red;
        }

        input[type="password"] {
            width: 250px;

        }

        .cont1ele {
            overflow: hidden;
        }

        /* #password{
            margin-left: 400px;
        }
        #login{
            margin-left: 200px;
        } */
        .login {
            margin-left: 200px;
        }
    </style>
</head>

<body>

    <nav>
        <div class="nav">BloodBank.com <br> A Social Initiative
            <div class="password">
                <div style="margin: 5px;">Password <input type="password" placeholder="Password"></div>
                <div>Donor Login <input type="password" placeholder="Username"></div>
                <div class="button"><button>Login</button></div>
            </div>
        </div>
    </nav>

    <div>
        <nav class="subnav">
            <a href="register.html" target="_blank">REGISTER</a>
            <a href="whydonate.html" target="_blank">WHY DONATE BLOOD</a>
            <a href="who.html" target="_blank">WHO CAN GIVE BLOOD</a>
            <a href="referral.html" target="_blank">REFER A FRIEND</a>
            <a href="contact.html" target="_blank">CONTACT US</a>
        </nav>
    </div>
    <div class="container">
        <div class="container1">
            <h3>Find a Donor</h3>
            <p>State <br><input type="text"></p>
            <p>City <br><input type="text"></p>
            <p>Area <br><input type="text"></p>
            <p>Group <br><input type="text"></p>
            <p class="searchbutton"><button>Search</button></p>
        </div>
        <div class="container2">
            <img src="OIP.jpg" alt="" height="350px" width="900px">
        </div>
    </div>
    <div class="container3"><strong style="margin-left: 550px;"> DONATION PROCESS</strong> <br>
        <p class="para">The entire process of donating whole blood (that is, blood with all component cells) takes about
            1 hour.
            Blood
            donors must be at least 17 years old (16 in some places with consent of a parent or guardian) and weigh at
            least
            110 pounds (50 kilograms). In addition, they must be in good health. Their pulse, blood pressure, and
            temperature are measured, and a blood sample is tested to check for low blood count(anemia).Donors are asked
            a series of questions about their health, factors that might affecttheir health, and countries they have
            visited.
            Certain conditions and factors can permanently or temporarily disqualify people from donating blood.
            disqualifying factors typically are those that might make donation dangerous for the donor or risk
            transmitting a disorder to the recipient.The decision to accept or disqualify a donor can be complicated.

        </p>
    </div>
    <div class="container4">
        <p><strong>Where would you like to donate?</strong></p>
        <select name="" id="">

            <option value="">--select--</option>
            <option value="jalandhar">Jalandhar</option>
            <option value="amritsar">Amritsar</option>
            <option value="phagwara">Phagwara</option>
        </select>
        <button>Submit</button>
    </div>
    <p>
        <textarea class="feedback" name="feedback" placeholder="Give Feedback" id="Address" cols="13" rows="5"
            required></textarea>
    </p>


</body>

</html>

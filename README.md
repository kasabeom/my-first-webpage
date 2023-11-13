# my-first-webpage
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sakshi parlour - ok11</title>
    <link rel="icon" href="">
    <style>
        body {
            margin: 0%;
            padding: 0%;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #ba8efd;
        }

        header,
        footer {
            background-color: #8d5ad8;
            color: rgb(154, 178, 198);
            text-align: center;
            padding: 2px;
        }

        .navitem {
            display: inline;
            padding: 15px;
        }

        .navitem a {
            text-decoration: none;
            color: aliceblue;

        }

        .Registretion {
            width: max-content;
            margin-left: auto;
            margin-right: auto;
        }

        .pricetable {
            text-align: center;

        }

        table {
            margin-right: auto;
            margin-left: auto;
            width: 100%;
            border-collapse: collapse;
        }

        th,
        td {
            border: 1px solid #8d5ad8;
            padding: 8px;
        }

        .contact-us {
            text-align: center;
        }

        .map {
            text-align: center;
        }
    </style>

</head>


<body>

    <header>
        <h1 style="background-color: aliceblue;">Sakshi Beauty Parlour,Bhoom</h1>
        <nav>
            <ul>
                <li class="navitem"><a href="#Registretion"></a>Registretion</li>
                <li class="navitem"><a href="#information"></a>Information</li>
                <liclass="navitem"><a href="#contact-us"></a>Contact Us</li>

            </ul>
        </nav>
    </header>

    <div style="position: relative; width: 100%; height: 0; padding-top: 56.2225%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
        <iframe loading="lazy"
            style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
            src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAF0CO6dQJQ&#x2F;view?embed"
            allowfullscreen="allowfullscreen" allow="fullscreen">
        </iframe>
    </div>
    <a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAF0CO6dQJQ&#x2F;view?utm_content=DAF0CO6dQJQ&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link"
        target="_blank" rel="noopener"></a>

    <section id="Registretion" class="Registretion">
        <h2>Registretion Form</h2>
        <p>Fill the below form to register as <em>student.</em></p>
        <form>

            <label for="name">Name: </label>
            <input type="text" placeholder="Enter name" id="name">
            <br>
            <br>
            <label for="email">Email: </label>
            <input type="email" placeholder="Enter Email" id="email">
            <br>
            <br>
            <label for="number">Mobile no.: </label>
            <input type="number" placeholder="Enter Mo." id="number">
            <br>
            <br>
            <lable for="password">password: </lable>
            <input type="password" placeholder="Enter password" id="password">
            <br>
            <br>
            <label for="DOB">Enter your DOB: </label>
            <input type="date" placeholder="birth date" id="DOB">
            <br>
            <br>

            <label for="age">Select age: </label>
            <select id="age">
                <option value="16-20">16-20</option>
                <option value="21-25">21-25</option>
                <option value="26-30">26-30</option>
                <option value="31-35">31-35</option>
                <option value="36-45">36-45</option>
            </select>
            <br>
            <br>
            <label for="file"> Upload photo: </label>
            <input type="file" value="file" id="file">
            <br>
            <br>
            <input type="checkbox" id="terms" value="agree">
            <label for="terms"> I agree on the terms and conditions.</label>

            <br>
            <br>
            <input type="reset">
            <input type="submit">


        </form>
    </section>
    <section id="information" class="pricetable">
        <h2>Cource information</h2>
        <p>Each cource is one month program.</p>
        <table style="border: 2px;">
            <tr>
                <th>parlour training</th>
                <th>tailor training</th>
                <th>Both</th>
            </tr>
            <tr>
                <td>Rs.7000</td>
                <td>Rs.5000</td>
                <td>Rs.10,000</td>
            </tr>
        </table>
    </section>
    <section id="contact-us" class="contact-us">
        <h2>Contact Us</h2>
        <p>You can contact us at <a
                href="https://www.google.com/maps/place/Sakshi+Beauty+Parlour,+Bhoom/@18.4607227,75.658446,17z/data=!4m9!3m8!1s0x3bc4e3045791b5d3:0xd0dd10c46ebab9df!8m2!3d18.4607176!4d75.6610209!10e4!16s%2Fg%2F11llnz55kl!18m1!2e1?entry=ttu">Ask
                a question</a></p>
        <p>You can contact us at company@official.com or visit us between 9AM to 6PM.</p>
        <p>Contact no: 9834054230.</p>

    </section>

    <iframe class="map"
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3784.506062471192!2d75.6584459747876!3d18.460722671000454!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bc4e3045791b5d3%3A0xd0dd10c46ebab9df!2sSakshi%20Beauty%20Parlour%2C%20Bhoom!5e0!3m2!1sen!2sin!4v1699873313627!5m2!1sen!2sin"
        width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy"
        referrerpolicy="no-referrer-when-downgrade">
    </iframe>
    <footer>
        <p>&copy; 2023 Sakshi Parlour, Bhoom </p>
    </footer>

</body>

</html>

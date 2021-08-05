# PHP mailer for HTML Forms

[PHPMailer](https://github.com/PHPMailer/PHPMailer) is used in this app

## Features

auto Reply to user on form sent

Redirect on form submition

## Setup

[Relpit](https://replit.com/~)

[More Help](https://mail.magma-mc.net/assets/html/help.html)

### mail.ini.php

edit the values

`User1` To the email of form

`Pass1` To the app password for email


### Assets/html/help.html

edit the value `https://mail.magma-mc.net` to your website

        <textarea cols="130" rows="30" name="index.html" readonly>
    <html lang="en">
        <head>
            <title>template</title>
            <script src="Mail.js"></script>
        </head>
        
        <body>
            <form id="index" action="https://mail.magma-mc.net" method="POST">
                <div class="input-holder">
                    <input class="input" name="Form[Email]" id="Email" type="email" value="" placeholder="email">
                </div>

                <div class="input-holder">
                    <input class="input" name="Form[Message]" id="message" type="text" value="" placeholder="Message">
                </div>

                <div id="PHP values">
                    <input name="Form[Message]" id="Message" type="hidden" value="Null">
                    <input name="Form[subject]" type="hidden" value="Subject Here">
                    <input name="Form[Admin_Email]" type="hidden" value="YourEmail@gmail.com">
                </div>

                <button class="button" type="submit" onclick="compile_message()">Sumbit</button>

            </form>
        </body>
    </html>
        </textarea>


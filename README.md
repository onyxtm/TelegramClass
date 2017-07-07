# TelegramClass
Telegram Class , متد های تلگرام :-)

# روش کار
        define("API_KEY", "Token");
        //Or
        $token = API_KEY;

        $telegram = new Magicode();

        $data = [
           "chat_id" => 322242763,
           "text" => "Your Text"
        ];

        $telegram->sendMessage($token or API_KEY, $data);
        
در هر جا که میخواهید استفاده کنید آن را قبل از همه کد ها include کنید

# برنامه نویسان

مرتضی باقری ، تیم مجیکد ، سل گیت

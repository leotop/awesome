Получить IP адрес по домену

    string ip = System.Net.Dns.GetHostEntry("ДОМЕН").AddressList[0].ToString();
    return ip;

Получить название кубика в котором ошибка

    return project.GetLastError().ActionComment;


Поиск значения переменной на странице

    // https://zennolab.com/discussion/threads/proverka-nalichija-vydelennogo-teksta.48822/#post-365321
    // Проверка наличия текста из переменной в активной вкладке.

    if(instance.ActiveTab.PageText.Contains(project.Variables["TEXT"].Value)){
        return "OK";
    }else{
        throw new Exception();
    }


Коллекции сниппетов

* https://github.com/ZennoHelpers/Snippets


Ссылки на темы:

* https://zennolab.com/discussion/threads/najti-koordinaty-4x-tochek-ehlementa-i-sdelat-randomnyj-klik-vnutri-ehtix-koordinat.66011/
* https://zennolab.com/discussion/threads/post-zapros-v-calendar-google-com.51626/
* https://zennolab.com/discussion/threads/vremja-ozhidanija-sms.36340/
* https://zennolab.com/discussion/threads/kak-perenesti-neskolko-strok-s-odnogo-spiska-v-drugoj.65705/
* https://zennolab.com/discussion/threads/c-snippet-kak-vzjat-stroku-iz-spiska-s-udaleniem.47055/
* https://zennolab.com/discussion/threads/vzjat-stroku-iz-spiska-s-posledujuschim-udaleniem-c.41188/
* https://zennolab.com/discussion/threads/10-sluchajnyx-chisel-diapazone-ot-0-do-100-bez-povtorov-s.65634/
* https://ru.stackoverflow.com/questions/18507/%D0%9A%D0%B0%D0%BA-%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B8%D1%82%D1%8C-%D0%B1%D1%80%D0%B0%D1%83%D0%B7%D0%B5%D1%80-%D0%B8-ip-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F

* https://ru.stackoverflow.com/questions/498038/%D0%9A%D0%B0%D0%BA-%D0%BE%D0%B1%D0%BE%D0%B9%D1%82%D0%B8-%D0%B2%D1%81%D0%B5-%D1%84%D0%B0%D0%B9%D0%BB%D1%8B-%D0%B2-%D0%BF%D0%B0%D0%BF%D0%BA%D0%B5-%D0%B8-%D0%BF%D0%BE%D0%B4%D0%BF%D0%B0%D0%BF%D0%BA%D0%B0%D1%85-%D0%B8-%D0%B4%D0%BE%D0%B1%D0%B0%D0%B2%D0%B8%D1%82%D1%8C-%D1%82%D0%B5%D0%BA%D1%81%D1%82-%D0%B2-%D0%BA%D0%B0%D0%B6%D0%B4%D1%8B%D0%B9-%D1%84%D0%B0%D0%B9%D0%BB-%D0%B2-%D0%A1-%D1%88%D0%B0%D1%80%D0%BF
* https://zennolab.com/discussion/threads/kak-izmenit-znaki-voprosov-na-russkie-slova.63416/
* https://zennolab.com/discussion/threads/uskorennyj-skroll-na-sharpe.63415/

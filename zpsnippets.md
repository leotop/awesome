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




Ссылки на темы:

* https://zennolab.com/discussion/threads/najti-koordinaty-4x-tochek-ehlementa-i-sdelat-randomnyj-klik-vnutri-ehtix-koordinat.66011/
* https://zennolab.com/discussion/threads/post-zapros-v-calendar-google-com.51626/


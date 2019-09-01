Получить IP адрес по домену

    string ip = System.Net.Dns.GetHostEntry("ДОМЕН").AddressList[0].ToString();
    return ip;


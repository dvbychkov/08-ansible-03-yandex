
«Использование Ansible» - «Бычков Денис Вячеславович»      
    
--- 

Основная часть

<img src = "img/11.JPG" width = 50%>

<img src = "img/ya.JPG" width = 50%>

1. Допишите playbook: нужно сделать ещё один play, который устанавливает и настраивает LightHouse.

2. При создании tasks рекомендую использовать модули: get_url, template, yum, apt.

3. Tasks должны: скачать статику LightHouse, установить Nginx или любой другой веб-сервер, настроить его конфиг для открытия LightHouse, запустить веб-сервер.

4. Подготовьте свой inventory-файл prod.yml.

<img src = "img/prod.JPG" width = 50%>

5. Запустите ansible-lint site.yml и исправьте ошибки, если они есть.

<img src = "img/2.JPG" width = 50%>

<img src = "img/3.JPG" width = 50%>

6. Попробуйте запустить playbook на этом окружении с флагом --check.

<img src = "img/check.JPG" width = 50%>

7. Запустите playbook на prod.yml окружении с флагом --diff. Убедитесь, что изменения на системе произведены.

<img src = "img/diff1.JPG" width = 50%>
<img src = "img/diff2.JPG" width = 50%>

8. Повторно запустите playbook с флагом --diff и убедитесь, что playbook идемпотентен.

9. Подготовьте README.md-файл по своему playbook. В нём должно быть описано: что делает playbook, какие у него есть параметры и теги.

10. Готовый playbook выложите в свой репозиторий, поставьте тег 08-ansible-03-yandex на фиксирующий коммит, в ответ предоставьте ссылку на него.


















<img src = "img/1.JPG" width = 50%>

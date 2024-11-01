# Программа для рассылок
Данная программа поможет вам отсылать шаблонные письма на указанные вами почты.

## Инструкция по настройке
### Подключение
Для подключения программы к вашей почте вам нужно создать пароль для приложений.
Как это сделать:

1. Открыть "Управление аккаунтом в Google".
2. Перейти во вкладку "Безопасность".
3. Настроить двухэтапной аутентификация (Если она у вас не настроена).
4. В поиске написать "password" и открыть "пароли приложений".
5. Называете ваше приложение и получаете пароль.
6. Данный пароль и почту, с которой вы будите отсылать письма, необходима внести в файл *auth.py*.

### Настройка шаблона
#### Тема письма
Для указания темы необходимо ее записать в переменную *them* в файле *auth.py*.
#### Текст письма
Созданные вами шаблон текста письма необходимо поместить в файл *text.txt*.
#### Фотография
Вместо фотографии *photo.jpg* добавьте свою с таким же названием.

### Ввод и запуск программы
#### Ввод списка писем
Все почты, на которые вы хотите отправить письмо, необходимо указать в файл *email.txt* через *enter*.
#### Запуск
Откройте файл *main.py* и запустите его. В консоль будет выводиться сообщение об успешной отправке письма на почту. 

## Предостережения
При частой отправке писем с одной и той же почты, письма могут попадать в спам или вообще не отправляться, при этом отследить данную проблему проблематично.

**Совет** - используйте разные почты и не злоупотребляйте рассылками. 
<h1 align="center">VK-Listener</h1>

<h2>VK-Listener - Модуль для Накрутки Прослушиваний в Вашем или Любом Другом Альбоме в Социальной Сети ВКонтакте

<h4>1. Установите chromedriver.exe Вашей версии Google Chrome<h3>
<h4>2. Перетащите chromedriver.exe в C:\Users\User\AppData\Local\Google\Chrome<h4>
<h4>3. Если нет папки, то создай её<h4>

```python
import vk-listener

listener.init('hide')

listener.authorization('Логин', 'Пароль')

if(listener.check()):
	print('Авторизация прошла успешно!')
else:
	print('Ошибка авторизации!')

listener.loop('Ссылка на Ваш альбом', 15)
```

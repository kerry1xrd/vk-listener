<h1 align="center">Raidium</h1>

<h3>Module for Cheat Listening in your Album on the VKontakte Social Network<h3>

<h4>1. Install <a href="https://chromedriver.chromium.org/downloads">chromedriver.exe</a> of your version of Google Chrome<h3>
<h4>2. Drag <a href="https://chromedriver.chromium.org/downloads">chromedriver.exe</a> to C:\Users\User\AppData\Local\Google\Chrome<h4>
<h4>3. If there is no folder, then create it<h4>

<h3>A simple code example using the "Raidium" library<h3>

```python
import raidium

raidium.begin('hide')

raidium.authorization('Login', 'Password')

raidium.loop('Album link', 15)
```

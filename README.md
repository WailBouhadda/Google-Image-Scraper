# Google Image Scraper With Selenium

### To use this code just install the selenium chrome web driver by downloading **the executable** or use **this code** :

```ruby
!pip install webdriver-manager
!pip install webdriver-auto-update

from selenium import webdriver
from selenium.webdriver.chrome.service import Service as ChromeService
from webdriver_manager.chrome import ChromeDriverManager

driver = webdriver.Chrome(service=ChromeService(ChromeDriverManager().install()))
```

### Next you will need to add your keywords to this list like this :

```ruby
keywords = ['Keyword 1', 'Keyword 2', 'Keyword 3', ...]
```

### And just run the code in a jupyter notebook and wait for it to finish

In general one keyword will give you about 350 - 600 image.

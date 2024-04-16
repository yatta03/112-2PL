the target website is <https://bhuntr.com/tw/competitions>
goal:

<p>get the information of processing competitions(including title, due day, prize, page link, tags), and I want to record all of the appeared tags.</p>
<p>considering the future use, i want to make it possible and fast to give relavant competitions when given a tag</p>

<br>
running hw3.ipynb create 3 file:

- competitions.json: records all competitions information
- tags.csv: including all unique tags in competitions
- relations.csv: records all tag and competition relation
  <br>

some mainly used functions:

- getOneCompetition()
- getAllCompetition()
  <br>

and a class:

- class Crawler  
   <br>

sth can be done in the future:

- optimize the crawling time
  - currently i'm using threading, but in semaphore(2), the affect is not visible, and the cpu usage will be horrible if I set larger number
- visualize the similarity between competitions by their shared tags
- build the recommand system

---

ref:  
[setting selenium](https://www.selenium.dev/blog/2023/headless-is-going-away/)  
[selenium wait function](https://www.learncodewithmike.com/2020/06/python-selenium-waits.html)  
[Python 多執行緒 threading 模組平行化程式設計教學](https://blog.gtwang.org/programming/python-threading-multithreaded-programming-tutorial/)

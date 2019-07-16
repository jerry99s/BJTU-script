Courses Automatic Section @BJTU2018-2019
======
## Environment requirement：
  * python
  * selenium library
  * chrome webdriver
  
------
## Settings：
  * ### user_id_str：<br>
      your student id.<br>
  * ### password_str：<br>
      the passord for mis.<br>
  * ### target cources(take chrome as example)：<br>
      press f12 and choose the most left column of this cource;<br>
      right click -> copy Xpath;<br>
      then replace the text in driver.find_element_by_xpath() at def duoxuan() by what you have copyed.<br>
  * ### delta:<br>
      time period of refreshing. 1s is enough.

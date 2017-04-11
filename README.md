**CS307 - Assignment 3 (NAGIOS)**
## Group 5
Arpit Karwasara - B14104
Ashish Arya     - B14106
Sagar Kaushal   - B14127
Shashank Sethi  - B14232

### SCHEDULE 1
#### Time :- 7:30 AM to 2:00 PM
#### Day :- THURSDAY
****
####  WEBSITE : insite.iitmandi.ac.in
****
- The ping RTT stays low except spiking around noon , which is explained by increased server traffic after classes.
- CPU load remains almost constant while increasing a little which is explained by students being in class and using insite after class hours.
- The RAM Used keeps on decreasing since the user requests become less file intensive and low memory is used.
- User load is less in the morning hours, and is increased after 10 AM.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/thu_ins.png">](thu_ins.png)


****
####  WEBSITE : students.iitmandi.ac.in 
****
- The ping RTT stays low except spiking around noon , which is explained by increased number of students checking mail after classes.
- CPU load remains low in early morning and then abruptly increases around 11:00 AM to reach a steady value which is explained by more students using webmail after classes.
- The RAM Used keeps on decreasing since the user requests become less file intensive and low memory is used.
- User load is very less in the morning hours, and reaches as high as 250 in the afternoon. This is consistent with the reasons for above observations.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/thu_stu.png">](thu_stu.png)


****
####  WEBSITE : webopac.iitmandi.ac.in
****
- The ping RTT stays low except a few spikes in RTT which is explained by random increase in number of students accessing the portal , otherwise one can see a steady increase in the average value due to more students accessing portal after noon.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/thu_web.png">](thu_web.png)


****
####  WEBSITE : network.iitmandi.ac.in
****
- The ping RTT spikes at around 11 AM, as is the case with other websites.
- CPU load is proportional to the user load. This can be seen in the plots.
- RAM usge is more or less constant.
- User load is not as high as it is for webmail, insite servers.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/thu_net.png">](thu_net.png)


****
****
### SCHEDULE 2 
#### Time :- 7:30 AM to 2:00 PM
#### Day :- SATURDAY
****
####  WEBSITE : insite.iitmandi.ac.in
****
- The RTT averages around 12 ms and most of the values are low because it is an saturday morning and most of the students will sleep till late resulting in a low network congestion.
- The graph for CPU LOAD keeps on rising till 2:00 PM because as more users log in to insite and more requests keep on coming the processing load increases.
- The RAM usage remains low in early mornings and increases around morning arriving steadily at an constant value in noon , due to late morning moodle usage.
- User load increases in the later half, not because of class schedules, but because it is a non-working day.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/sat_ins.png">](sat_ins.png)


****
####  WEBSITE : students.iitmandi.ac.in 
****
- The ping RTT average time is around 9 ms and remains low for most of the time since mainly of two reasons , students waking up late on a weekend and also due to exodia low traffic usage results in low congestion and so low RTT.
- The CPU Load is generally low , having a peak at around noon time which is explained bye students checking more mail at late morning hours.
- The RAM load initially remains almost constant and abruptly increases around noon which is explained by high memory requirements for files download by students logging into the mail server.
- User load follows the same trend as insite, reason being that Saturday is a non-working day, and it is unlikely that most people would check their mails in the morning hours.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/sat_stu.png">](sat_stu.png)


****
####  WEBSITE : webopac.iitmandi.ac.in
****
- The ping RTT stays low around early morning hours and then steadily keeps on increasing as the morning progresses which is explained by beforementioned reasons.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/sat_web.png">](sat_web.png)


****
####  WEBSITE : network.iitmandi.ac.in
****
- The ping RTT spikes at around 11 AM, as is the case with other websites.
- RAM usge is more or less constant.
- User load is not as high as it is for webmail, insite servers.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/sat_net.png">](sat_net.png)


****
****
### SCHEDULE 3 
#### Time :- 7:30 AM to 2:00 PM
#### Day :- MONDAY
****
####  WEBSITE : insite.iitmandi.ac.in
****
- The ping RTT averages around 10 ms and the high RTT region lies around 9:00 AM to 11:00 AM and 12:00 to 2:00 PM due to more network usage during these times which leads to higher congestion resulting in more RTT .
Also packet loss stays averages to 0% and the max reaches to 3%.
- The CPU load around 8:00 AM is low due to less processing usage in retrieval of queries , because in the moring less number of queries are there but since the students  start using moodle to study after classes which is the major traffic source for insite , the CPU Load keeps on increasing till 2:00 AM. 
- The RAM usage is initially high and then keeps on decreasing.
- User load is increased in the later half, as was the case on Thursday schedule.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/mon_ins.png">](mon_ins.png)


****
####  WEBSITE : students.iitmandi.ac.in 
****
- The ping RTT averages around 10 ms and the high RTT region lies around 9:00 AM to 11:00 AM and 12:00 to 2:00 PM due to more network usage during these times which leads to higher congestion resulting in more RTT since people are more likely to check webmail during these hours which is the main source of traffic.
- The CPU load tends to be higher after 12 Noon , since people are more likely to use webmail after class hours.
- The RAM usage initially increases till noon due to more file load on the server and then abruptly falls.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/mon_stu.png">](mon_stu.png)


****
####  WEBSITE : webopac.iitmandi.ac.in
****
- The ping RTT averages around 10 ms and the high RTT region lies around 9:00 AM to 11:00 AM and 12:00 to 2:00 PM due to more network usage during these times which leads to higher congestion resulting in more RTT since these corresspond to study hours.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/mon_web.png">](mon_web.png)


****
####  WEBSITE : network.iitmandi.ac.in
****
- The ping RTT spikes at around 11 AM, as is the case with other websites.
- RAM usge is more or less constant.
- User load is not as high as it is for webmail, insite servers.
[<img src="https://github.com/bittikarwasara/systemprac/blob/master/mon_net.png">](mon_net.png)


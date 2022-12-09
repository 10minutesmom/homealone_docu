# homealone_docu
Tech blog link=https://helix-evening-373.notion.site/HOME-ALONE-34634be4455f4dd9a5b7a8c490dc4f03

# introduction
Childcare has been a major issue due to the rapid growth of dual-income families. Home Alone application is willing to solve the problems that arise from this type of family. Home Alone supervises a child alone at home in two terms. 

First, Home Alone enables parents to detect the location of the child inside the house in real-time. Previous technologies mostly focused on searching for a target location outside rather than inside. There are two reasons for this. First, indoors was commonly considered to be safer than outdoors. Second, due to privacy issues, companies were reluctant to detect the target inside. Thus, by focusing on the detection of the location and the kid’s current status inside the house, this application is differentiated from current applications on the market. In addition, by adopting robot cleaner, Home Alone minimized the risk of invasion of privacy during the process.

Second, Home Alone works as a child’s personal scheduler. A station tells the kid about an upcoming schedule and alarms children to get ready for the next schedule. This application alarms repeatedly so that he or she can wake up on their own. This will alleviate parents’ worries about their kid being late.

By combining two features, Home Alone can also report to the parents if the kid is laying in bed when the next schedule is imminent. Then the parents can take an action, such as making a call to their kid. In short, this application can relieve parents from their anxiety about their kids being alone at home.

# Core function

**Detect child location in house (집 내의 아이 위치 파악)**

Combining LG robot vacuum and ThinQ APP, it can detect kid's location inside house.
When LG robot vacuum captures 5 pictures and send them to station, Homealone Station detects kid's existance utilizing ML algorithm.


**Detect child`s pose(아이의 현 상태 파악)**

LG 로봇 청소기의 홈뷰 기능을 이용하여 다섯장의 사진을 THINQ앱으로 부터 전송받으면, Homealone Station 디바이스에서 ML 알고리즘을 이용하여 사진 속 아이의 상태를 앉아있기, 누워있기, 서 있기로, 세 가지로 분류합니다.

**Manage schedule(스케줄 관리(자동화))**

원격으로 관리하기 어려운 아이의 스케줄을 간편하게 관리할 수 있습니다. 아이의 스케줄을 등록하면, HOME ALONE 앱은 해당 스케줄의 준비시간을 고려하여 아이의 다음 스케줄을 준비시킵니다. 만약, 아이의 상태가 다음 스케줄에 준비되지 않은 경우(누워있거나 앉아있는 경우), 아이를 깨우고, 현재 상황에 대해 부모에게 sms를 보냅니다. 또한, 아이가 스케줄상 집에 있어야 할때, 집에 없는것이 감지된 경우, HOMEALONE 앱은 SMS를 통해 부모에게 아이가 없음을 알립니다.

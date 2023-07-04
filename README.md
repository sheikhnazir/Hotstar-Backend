# Hotstar-Backend
Hotstar application is a spring project that you need to create. There is already a prewritten code that is being written, you need to complete the other remaining part of the code.

Understanding of the problem statement :

Customer and Subscription is One:One mapping only. There are 3 types of subscriptions available : BASIC PRO ELITE

ELITE >> PRO >> BASIC

There are 2 types of facilities that are available (Webseries and match) , some web series are available with BASIC plan and some are available with PRO plan only. To see matches you need to have the ELITE subscription. If you have an ELITE subscription you can watch any match or web series. If you have PRO subscription you can watch the PRO web series as well as those of BASIC plan webseries.

The subscription costing goes something like this. There is only monthly subscription possible :

For Basic Plan : 500 + 200noOfScreensSubscribed For PRO Plan : 800 + 250noOfScreensSubscribed For ELITE Plan : 1000 + 350*noOfScreensSubscribed

Production House : This is the production house which is producing the webseries. The production house’s rating is the average of all the webSeries it has produced. For eg if 2 webseries have a rating of 4 and 5. Then the productionHouse’s rating is the avg of 4.5 ratings.

There are football matches going on Hotstar, each match is of 90 mins of duration. And 2 teams playing that match

Note : Don't change the underlying/existing code Please don’t use the lombok library, (No Getters, Setters, @Builder etc). You can always create these functions manually as and when required. You can create new functions/methods/constructors incase you need them, but dont delete or modify the existing code. In case the @Autowired annotation doesn’t work please connect them via a new keyword object and then you can call these methods using that object.

//tutuytuy
newtaskObj = Collection();
taskID = {"id","owner"}; 
result = taskID.get(1);

sendmail
[

	From: "help@tavriav.com.ua"
	to:  "n.shapovalov@tavriav.com.ua,a.yashin@tavriav.com.ua,v.kosyh@tavriav.com.ua,v.levadnij@tavriav.com.ua,j.yaroschuk@tavriav.com.ua,sergk@tavriav.com.ua,s.wollenberg@tavriav.com.ua"
	subject: "Сообщение системы поддержки"
	message:"<div> Кассовый на новом объекте ТЦ Атриум установлен и включен. Прошу принять в работу </div>"
]
//Message to be printed in Request history
returnObj = Collection();
returnObj.insert("result":"success");
returnObj.insert("message":"High Priority Request Mail sent successfully");
return returnObj;

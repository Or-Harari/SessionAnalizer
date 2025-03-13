All reqests must contain the relevant cookies in the header, Glogs login cookies.

For now, the following Cookies will work - 
hubspotutk=8d4d9b0bdcdee6b09f7402d8c81ff56e; _hjSessionUser_2023722=eyJpZCI6Ijg4M2VjZDQzLWFmZDctNTljZi1iNTBhLTNjZGRkNWY3YTQ4ZiIsImNyZWF0ZWQiOjE3NDA1NjE0MjkyNzMsImV4aXN0aW5nIjpmYWxzZX0=; ai_user=n7+Pt|2025-02-26T09:36:35.613Z; _gid=GA1.2.2061099910.1741774329; _ga_V12NX2FNY9=GS1.2.1741774329.7.1.1741774576.0.0.0; _ga=GA1.1.314425620.1739717085; __hstc=117909590.8d4d9b0bdcdee6b09f7402d8c81ff56e.1739720565240.1741178457486.1741774664391.4; __hssrc=1; __RequestVerificationToken=n6csoeI3zkLiA-CNYTio3yp0WSuh-I_mj5dNO0-psowgg24dkPmmQgvOn0dzI1EXfibDYJpSyb8vPvyH-Xpc_tVC_G3fo3JQVADYrTnSbBY1; ARRAffinity=9711c419a659049fd2590cda84358b6b7fe4a165cdb6acbb6ef91d696e076af4; ARRAffinitySameSite=9711c419a659049fd2590cda84358b6b7fe4a165cdb6acbb6ef91d696e076af4; div2unc0fa69b30a132fb28c6c4a15df990121fc28bc75cb16eaa6b6f813bd248ece17=or_harari; ASP.NET_SessionId=bid4l2me0qqv5lzhhr3njlvp; _ga_1DY638GTQS=GS1.1.1741774663.7.1.1741775048.0.0.0; .ASPXAUTH=8A86C34A18CFCEB87533C391B684320F71892383AFF73EFCE189F6F04744EB3688541D9EE9D2BC82A4E33C92E1C33165A46DF84DD564F9FBCED82D048BDB77FF30CA9BDBFABD891B3B40EE8E4DF4850B0FC8448360B8EBF7AB672D4205D67BCE;
----------------------------------------------------------------------------------------------------------
Search for the session values(environemnt, AffiliateId, UserName,  etc...)based on a sessionID -
Endpoint GET - https://logs.hsp.gimmonix.com/Sessions/SearchSessionOrSegment?value=%2F22%2F143212%2FD20250313T090514%2Faf1cd7da41b54f129976728222fa69f4

-----------------------------------------------------------------------------------------------------------
Endpoint POST - https://logs.hsp.gimmonix.com/Sessions/Sessions
headers{
Cookies - [Glogs - cookies]
ContentType - x-www-form-urlencoded
}
REQ Body:
{
  "Date": "12/03/2025",
  "AffiliatedId": 61,
  "AvailableEnvironments": 0,
  "EnvironmentId": 0,
  "UserId": 551,
  "UserName": "sigita@westexpress.lt",
  "SessionId": "/61/551/D20250312T113417/c9574680cb9447ce9e2d7282aa31ebe5/",
  "SessionSuffix": "D20250312T113417/c9574680cb9447ce9e2d7282aa31ebe5/",
  "Time": "12/03/2025 11:34:17"
}  

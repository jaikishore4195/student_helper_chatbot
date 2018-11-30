# student_helper_chatbot (Work in progress)
Chatbot implemeted from scratch without using any bot framework, students can use this chat-bot to query about their classes,assignments, locations,etc


ModelIntroduction:  Built  a  Chatbot  where  students  can  query  about  their  classes,  timings,  location,  assignment  reminders  and  also  added  small  talk  functionality  to  the  model.  

Natural  Language  Understanding  Engine:  Built  Custom  NLU  model  to  detect  the  intent  of  the  question  and  also  extract  the  entities  from  the  question.  For  training  the  NLU  model  created  the  data  using  chatito  and  then  built  a  shallow  network  with  dense  embeddings  to  classify  the  intent  and  did  the  entity  extraction  by  building  a  neural  network  to  do  sequence  tagging.  

Core  Engine:  The  core  of  the  model  is  used  to  decide  upon  which  action  need  to  be  performed  by  the  chatbot  next  and  for  the  core  of  the  chat  bot  wrote  a  functional  algorithm  and  actively  working  to  convert  the  core  of  this  chatbot  to  be  learning  capable.  

Small  talk:  Its  always  fun  to  have  the  chatbot  do  small  talk  to  trained  the  model  to  do  small  talk  with  cosine  similarity  question  matching  on  a  TFIDF  matrix.  Model  use  case  in  Industry:  Chatbots  have  multiple  applications  and  use  cases  where  they  can  be  implemented 

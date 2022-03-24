# Denis Martianov <h1>

# My Contact Info <h2>
\- Phone number: +7(931)311-10-22
\- GitHub: [frendorDM](https://github.com/frendorDM)
\- E-mail: frendor.dm@gmail.com

## About me <h2>

I am 24 years old, I work as a junior .Net BackEnd developer about six month. I like my job, but I want to learn Front development too. And I want work as a Full-Stack developer. And I need to get a lot of experience and knowledge in the field of development.

## My strengths: <h2>

I like to learn
I like to comminuty with my colleagues
I like new tasks 

## My weaknesses: <h2>

 I'm fearful
 I've been studying for a long time
 I don't speak English very well

## Skills <h2>

 \- Git/GitHub
 \- C#/.Net
 \- EF/Dapper
 \- Swagger
 \- MSSQL/MySQL/T-Sql

## Code Examples <h2>

```using System;
using System.Collections.Generic;
using System.Text;
using WebChatApp.Data;
using WebChatApp.Models;

namespace WebChatApp.Services
{
    public class ChatService : IChatService
    {
        private IChatRepository _chatRepository;

        public ChatService(IChatRepository chatRepository)
        {
            _chatRepository = chatRepository;
        }
        public Chat GetChatById(int id)
        {
            var dto = _chatRepository.GetChatById(id);
            return dto;
        }
        public int AddChat(Chat chatDto)
        {
            return _chatRepository.AddChat(chatDto);
        }
    }
}
```

## Educatiom <h2>

*Bachelor, Sant-Petersburg, Mining University 
    * Information technology
*Magister, Sant-Petersburg, ITMO University
    * Information technology
*Cours DeveEducation
    * C#
    * BackEnd development

## Language <h2>

Russian - native speaker
English - A2

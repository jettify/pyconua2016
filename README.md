# Building apps with asyncio

`asyncio` - is young library for asynchronous network programming. Lack of 
information on proper use and writing code in asyncio as well as production war
stories slows down its adoption.

In this talk I'll cover my experience with `asyncio` in production, best 
practices for writing reliable and testable asynchronous code as well as bunch of 
`asyncio` tips and tricks. We will discuss how run `asyncio` application in standalone
mode, execute blocking code in event loop and moreover how embed `asyncio`  in your
synchronous application. 

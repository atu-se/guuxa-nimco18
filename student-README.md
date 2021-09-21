
# Student README

## Questions

1. The client and server have different sized buffers.  Why does it still work?
>  server does not know about client's buffer
2. What happens if the buffer size on the client is changed to a value smaller than the initial message_length?
answer
> nothing happens it will remain the same.

3. What happens if you run the client when the server is not running? 
answer 
> No connection could be made becouse the target is not active.

4. What happens if you run the server while the server is already running?
answer 
> OSError
Only one usage of each socket address is normally permitted

5. What changes did you make to finish this assignment?

 I changed or modified server.py

6. What resources did you use to complete this assignemnt?  Make a Markdown list of web links below.
>https://www.youtube.com/watch?v=nmzzeAvQHp8
>https://www.youtube.com/watch?v=nmzzeAvQHp8
>https://www.youtube.com/watch?v=SepyXsvWVfo
>https://www.youtube.com/watch?v=bTThyxVy7Sk
# How to use rabbit-mq server and celery together
- Celery is a task queue/job queue based on distributed message passing. It is focused on real-time operation, but supports scheduling as well. The execution units, called tasks, are executed concurrently on a single or more worker servers.
- rabbit-mq is the message broker server

# How to use Multithreading in django to make django-api work faster
- import threading
- define a class
```py
class NotificationSend(threading.Thread):
  
  def__init__(self):
    self.email = recipient_email
    self.subject = subject
    self.message = message
    threading.Thread.__init__(self)
  def run(self):
    from_email="subhrajyotisankarsau@gmail.com"
    send_email(self.subject,message,from_email,self.email,fail_silently=false)
```
- whereever you want to implement the function call the function
- NotificationSend("subhrajyotisankarsau@gmail.com","notification","this is email send using multithreading").start() 

# django-multiprocessing
    
     
    
       

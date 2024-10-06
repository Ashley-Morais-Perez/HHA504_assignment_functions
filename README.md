
# HHA504_assignment_functions

### 1. Deploy a Serverless Function
- **Azure:**
 
  <img width="336" alt="image" src="https://github.com/user-attachments/assets/0800c685-a1db-45b3-b0d1-dbef95e7ac37">

<img width="719" alt="image" src="https://github.com/user-attachments/assets/921ab9fb-f11e-417c-9a25-99e5fecc60ca">

<img width="948" alt="image" src="https://github.com/user-attachments/assets/c8bd9dc2-f9c3-4538-904b-9686a035eeaa">

I was having trouble testing the 'name: value' function
<img width="286" alt="image" src="https://github.com/user-attachments/assets/b1d13b5c-67ae-439c-bc03-1f2e9499acd3">

Because I didn't seem to have access on the Azure portal, when I tried running the function in Cloud Shell Editor, the URL gave trouble with running the function

<img width="586" alt="image" src="https://github.com/user-attachments/assets/d01e2a0d-d8df-46a5-9ebc-db80b25df668">



- **GCP:**

<img width="602" alt="image" src="https://github.com/user-attachments/assets/2c490d8e-3920-4f4c-98a5-74702f0b51eb">

<img width="791" alt="image" src="https://github.com/user-attachments/assets/48cf71d7-87b1-4b56-b24c-93e8eaf43749">

The function provided the response with 'Hello Hello World' (which makes sense since the name used was 'hello world'

<img width="800" alt="image" src="https://github.com/user-attachments/assets/0feab779-3d87-4801-9c8c-ecfa5691d972">

Following the class video, I also changed 'name' to 'first name' and was able to produce 'Hello Ashley'

<img width="801" alt="image" src="https://github.com/user-attachments/assets/0926c3ea-fdf8-4f5a-8a10-8482b2a0f20a">

Tested the function on Google Colab, and produced the response 'Hello Ashley'

<img width="521" alt="image" src="https://github.com/user-attachments/assets/ed11354d-ad1a-4bd4-a180-e5333c89ccf6">

 
### 2. Create a Cron Job
- **GitHub Actions:**

  To create a Cron job, I used a template from Github 'Actions' to create a simple workflow.
  Every five minutes a single command line should run stating 'Hello World'

  <img width="939" alt="image" src="https://github.com/user-attachments/assets/0e4f2ad8-00bc-4400-b2c6-f1f4f339cadd">


### 3. Explore Functions as a Service (FaaS)

Serverless functions can help with web applications, scheduled tasks, and other data processing. The benefit of using Functions is that it seems much more manageable and efficient for someone who only needs to review data in real time. Functions would not be beneficial for someone who requires a system that is highly secure, can run for longer periods of time, and can manage more complex processes. 

# Chatbot-using-AIML-for-college-purposes.

what is chatbot?
Chatbots are programs that mimic human conversation using Artiﬁcial Intelligence (AI).It is an ultimate virtual assistant, helping one to complete tasks.
It is an interactive interface which provides the conversion between the human and the system.

About AIML: 
AIML stands for Artificial Intelligence Markup Language. AIML was developed by the Alicebot free software community and Dr Richard S. Wallace during 1995–2000. 
AIML is used to create or customize Alicebot which is a chat-box application based on A.L.I.C.E. (Artificial Linguistic Internet Computer Entity) free software.
             
Steps in building an AIML rule-based chatbot:

1)Install AIML modules.

2)Create a standard startup file.

3)Creating AIML Files.

4)Including random responses in AIML files.

5)Write a python program with brain module for faster response.


1.For Installing AIML modules:

  For python 2
        pip install aiml
  For python 3
        pip install python-aiml
                 OR
        pip3 install python-aiml

2. Creating a standard startup file:

It is standard to create a startup file called std-startup.xml as the main entry point for loading AIML files. In this case, we have create a basic file that matches one pattern and takes one action. We want to match the pattern load aiml b and have it load our aiml brain in response.



3. Creating AIML Files:

After creating the AIML file that only handles one pattern, load aiml b. When we enter that command to the bot, it will try to load basic_chat.aiml. It won’t work unless we actually create it.After that,We will match two basic patterns and respond.


It can be fun to write your own AIML files, but it can be a lot of work. I think it needs around 10,000 patterns before it starts to feel realistic. So feel free to use the AIML files available online.

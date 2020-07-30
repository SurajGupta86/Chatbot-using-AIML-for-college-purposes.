# Chatbot-using-AIML-for-college-purposes.

what is chatbot?
Chatbots are programs that mimic human conversation using Artiﬁcial Intelligence (AI).It is an ultimate virtual assistant, helping one to complete tasks.
It is an interactive interface which provides the conversion between the human and the system.

About AIML: 
AIML stands for Artificial Intelligence Markup Language. 
AIML was developed by the Alicebot free software community and Dr Richard S. Wallace during 1995–2000. 
AIML is used to create or customize Alicebot which is a chat-box application based on A.L.I.C.E. (Artificial Linguistic Internet Computer Entity) free software.
             


Steps:
Steps in building an AIML rule-based chatbot:
Install AIML modules.
Create a standard startup file
Creating AIML Files
Including random responses in AIML files.
Write a python program with brain module for faster response.
1. Install AIML modules:
For python 2
pip install aiml
For python 3
pip install python-aiml
OR
pip3 install python-aiml

2. Creating a standard startup file:
It is standard to create a startup file called std-startup.xml as the main entry point for loading AIML files. In this case, we will create a basic file that matches one pattern and takes one action. We want to match the pattern load aiml b and have it load our aiml brain in response.
<!-- In the file std-startup.xml -->
<aiml version="1.0.1" encoding="UTF-8">
    <category>

        <!-- Pattern to match in user input -->
        <!-- If user enters "LOAD AIML B" -->
        <pattern>LOAD AIML B</pattern>

        <!-- Template is the response to the pattern -->
        <!-- This learn an aiml file -->
        <template>
            <learn>basic_chat.aiml</learn>
            <!-- You can add more aiml files here -->
            <!--<learn>more_aiml.aiml</learn>-->
        </template>
        
    </category>

</aiml>
3. Creating AIML Files:
Above we created the AIML file that only handles one pattern, load aiml b. When we enter that command to the bot, it will try to load basic_chat.aiml. It won’t work unless we actually create it. Here is what you can put inside basic_chat.aiml. We will match two basic patterns and respond.
<!-- In file basic_chat.aiml -->
<aiml version="1.0.1" encoding="UTF-8">

    <category>
        <pattern>HELLO</pattern>
        <template>
            Well, hello!
        </template>
    </category>
    
    <category>
        <pattern>WHAT ARE YOU</pattern>
        <template>
            I'm a bot, silly!
        </template>
    </category>
    
</aiml>

It can be fun to write your own AIML files, but it can be a lot of work. I think it needs around 10,000 patterns before it starts to feel realistic. So feel free to use the AIML files available online.

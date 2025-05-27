# Hi there 👋

#!/usr/bin/python  
#-*- coding: utf-8 -*-  

<span style="color: blue">class</span> Explorer:   

    def __init__(self):
        self.name = "Constantin CHU"
        self.organization = "LogiControl"
        self.role = "Explorer"
        self.city = "shanghai_CN"
        self.language_spoken = ["zh_CN", "en_US"]
        self.interests = ["Investment", "Quant", "AI", "Robot"]  
        
    def say_hi(self):
        print("Hi Stranger.")  
        
me = Explorer()  
me.say_hi()

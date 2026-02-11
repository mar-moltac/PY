# PY
My cool python projects

pentester = "They hack sistems to test vulnerability of the system, their goal is to get them befores hackers do "
bugbountyhunter = " You search for weak points in a system to get bread in exchange "
redteaming = "They do targetted atacks to an organization defenses, looking to test the security measures of the sistem, they use any tactics necessary "
blueteaming = "Their job is to prevent atacks, they actively check logs, etc "
Security_Operation_Center = "They monitor systems 24/7 , responding to threats in real time"
Incident_Response_Team = "As their name says, after a system is atacked, it´s their jobs to remove any malware and work on solving the trouble caused by it"

#There are a lot more teams, this code only covers the atack and defense ones, ignoring hybrids, wich combines the efforts of both teams"

team = input("Enter your team ( pentester, redteaming , blueteaming , etc. ):  ").lower()
if team == "pentester" :
    print(pentester)
elif team == "redteaming": 
    print(redteaming)
elif team == "blueteaming": 
    print(blueteaming)
elif team == "bugbountyhunter": 
    print(bugbountyhunter)
elif team == "Security_Operation_Center":
    print(Security_Operation_Center)
elif team == "Incident_Response_Team":
    print(Incident_Response_Team)
else:
    print("Choose a Valid Team Bro")
identify = input("Wich of the past answers would you like to be:  ").lower()
if identify == "pentester" :
    print("Try to learn how to hack machines in HACK THE BOX  ")
elif identify == "redteaming":
    print("Join a corporation, there you can defend their ass.")
elif identify == "blueteaming":
    print("Join evilcorp, mr.robot will come for you too.....")
elif identify == "bugbountyhunter": 
    print("Search for zero days and sell them in the dark web ")
elif identify == "security_operation_center":
    print("You wont sleep looking for weak spots little buddy")
elif identify == "incident_response_team":
    print("You will always arrive late to the bug fixes.")
else:
    print("Be fr now dude, Im trynna help you get your life together.")


print("I hope this code helped you find your carrer path :) M.")

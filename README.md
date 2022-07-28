# Industrial-and-systems-engineering
# How-do-I-protect-my-robot
How to keep your Robot Safe 
Nothing on the Internet of Things is safe from hacking , and any links offer opportunities for cybercriminals to potentially exploit for harmful purposes . Here , we look at the main areas of threat and what you can do to keep your robot safe and secure .  
The 3 main ways that industrial robots tend to be hacked at present are :    
* Theft of information : obviously this depends on the tasks the robots are deployed to complete . Whilst robots used to stack pallets may not be of much interest to hackers , robots used in critical sectors such as defence , aerospace and energy may contain more sensitive , and therefore more attractive , information to cybercrims .
* Inflicting physical harm : this is where robots are hacked to introduce safety threats to the working environment . Examples here include where the robot reports back to its controller that it is powered down when it isn't , or the robot is programmed to behave erratically .
* Inserting microdefects : the robot is programmed to alter their processes and insert barely noticeable defects into the manufacturing . Again , this is dependent on the sector but the implications are potentially extremely serious for the food processing , aerospace , automotive and healthcare sectors .


# Secure by Design 
So what can be done to protect robots from being hacked ? Here are the key security issues which need to be addressed as a matter of course :
Insecure connections : the issue here is not the Bluetooth of wi - fi technology , as much as the transmission of data . Most data is unencrypted , and even some encryption methods can be hacked now . Encrypting data is now not enough , it has to be smartly encrypted . 
Insecure privacy protocols : reporting data remotely is a high - risk act , and strict privacy controls are required to reduce the potential points of entry for a hacker.
User authentication not strict enough : defining and authorising users may sound like an obvious process . Consider also using the Principle of Least Privilege - where users can only access the areas required for them to complete their tasks .
Default configuration security not tight : merely accepting the default settings could put your system at risk , as often these can be easily avoided . This covers the default configs , passwords , access levels , accounts and settings .

# International Standards 
The International Electrotechnical Commission ( IEC ) in agreement with the International Society of Automation ( ISA ) published a series of standards and technical reports that define procedures for implementing secure Industrial Automation and Control Systems ( IACS ) . The standard provides guidance to those that create products , integrate systems , and operate industrial automation and control systems .

• FR 1 Identification and authentication control ( IAC ) : protect the device by verifying the identity of and authenticating any user requesting access ; 
• FR 2 Use control : protect against unauthorized actions on the device resources by verifying that the necessary privileges have been granted before allowing a user to perform the actions ; 
• FR 3 System integrity : ensure the integrity of the application to prevent unauthorized manipulation ;
• FR 4 Data confidentiality : ensure the confidentiality of information on communication channels and in data repositories to prevent unauthorized disclosure ;
• FR 5 Restricted data flow : segment the control system via zones and conduits to limit the unnecessary flow of data ;
• FR 6 Timely response to events : respond to security violations by notifying the proper authority , reporting needed evidence of the violation , and taking timely corrective action when incidents are discovered ; and
• FR 7 Resource availability : ensure the availability of the application or device against the degradation or denial of essential services . If properly addressed , these requirements will reduce many cybersecurity risks across an industrial robot system .

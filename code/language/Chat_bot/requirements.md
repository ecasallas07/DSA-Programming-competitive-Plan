# System Requirements:

- A Twilio account and a smartphone with an active phone number and WhatsApp installed.
- Must have Python 3.9 or newer installed in the system.
- Flask: We will be using a flask to create a web application that responds to incoming WhatsApp messages with it.
- ngrok: Ngrok will help us to connect the Flask application running on your system to a public URL that Twilio can connect to. This is necessary for the development version of the chatbot because your computer is likely behind a router or firewall, so it isn’t directly reachable on the Internet.
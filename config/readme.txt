
sendEmail - Send email from a console near you!
Written by: TrongLG
https://www.facebook.com/tronglvIA


---------------
Usage Overview
---------------


Synopsis:  sendEmail -from sender_ADDRESS -to receiveder_ADDRRESS -tiltle SUBJECT -contents [Optional]

  Required:
    -from 	   EMAIL_ADDRESS                from (sender) email address
    -to   	   EMAIL_ADDRESS                to (receiveder) email address
    -title 	   SUBJECT                      message subject	
    -contents 	   [Optional]

  Optional:
    "Path_FILE"   				file attachment
    "Text_message"				message body

  Help:
    -help true                   the helpful overview you're reading now
 

---------------
Examples
---------------
 

Simple Email with text message:
  sendEmail -from me@gmail.com      \
            -to friend@gmail.com    \
            -title "Example about sending text message"  \
            -contents "Hi buddy, this is a test email."

Simple Email with attechment:
  sendEmail -from me@gmail.com          \
            -to friend@gmail.com    	\
            -title "Example about sending attachment" \
            -contents "D:\data\data.pdf"

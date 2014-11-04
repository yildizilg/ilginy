from urllib import urlopen
from os import system
import time

# for the emailing
import smtplib
from email.mime.multipart import MIMEMultipart
from email.mime.text import MIMEText


name1 	= "ilgin"
name2	= "yildiz";
name3 	= "alla";
name4	= "charniakova";

t = 0;
step = 15;
timestr = 0;
#time.sleep(40*60)
print("Program Starts!")

for t in range(0, 1200, step):

	ausgabewinner = urlopen("http://www.antenne.de/frames/rechnung/spezial_ausgabewinner_iframe.php").read()
	ausgabewinner = ausgabewinner.lower()
	#print(ausgabewinner)
	N1 = ausgabewinner.find(name1);
	N2 = ausgabewinner.find(name2);
	N3 = ausgabewinner.find(name3);
	N4 = ausgabewinner.find(name4);	
	print(t)

	lucky_name 		= ausgabewinner.find("<p><b>")
	lucky_name_end 	= ausgabewinner.find(": antenne bayern zahlt ihre")

	if timestr > 1:
		print ("Finalized : Antenne_Bayern_%s.txt" %timestr)
		for i in range(1,6):
			system("afplay /System/Library/Sounds/Purr.aiff")
		break
	else:
		if lucky_name>-1 and lucky_name_end>-1:
			timestr = time.strftime("%d%m%Y_%H%M%S")
			print(timestr)
			text_file = open("Antenne_Bayern_%s.txt" % timestr, "w")
			text_file.write("Lucky Name : %s" % ausgabewinner[lucky_name+6:lucky_name_end])
			text_file.close()

	if N1>-1 or N2>-1 or N3>-1 or N4>-1:
		print "CALL NOW --> 0800 994-1000"
		for i in range(0,20):
			system("afplay /System/Library/Sounds/Glass.aiff")

					# EMAIL #
		#=======================================================#
		me = "ilginyildiz86@gmail.com"
		you1 = "ilgin.yildiz@oncolead.com"
		you2 = "charniakova.alla@swm.de"
		
		# Create message container - the correct MIME type is multipart/alternative.
		msg = MIMEMultipart('alternative')
		msg['Subject'] = "JETZT ANRUFEN!!! - 0800 9941000"
		msg['From'] = me
		msg['To'] = you2
		
		# Create the body of the message (a plain-text and an HTML version).
		text = "Ich habe die Name gesehen:\n%s" % ausgabewinner[lucky_name+6:lucky_name_end]
		
		# Record the MIME types of both parts - text/plain and text/html.
		part1 = MIMEText(text, 'plain')
		
		# Attach parts into message container. According to RFC 2046, the last part of a multipart message, in this case
		# the HTML message, is best and preferred.
		msg.attach(part1)
		
		# Send the message via local SMTP server.
		mail = smtplib.SMTP('smtp.gmail.com', 587)
		
		mail.ehlo()
		mail.starttls()
		mail.login('ilginyildiz86', 'jucjvdpzvuzmpbel')
		mail.sendmail(me, you2, msg.as_string())
		mail.quit()
		print("Email sent to: %s" % you2)
		#=======================================================#
		break
	else:
		print "NOTHING!"
	time.sleep(step)


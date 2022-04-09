import smtplib

gmail_user = 'YOUR_GMAIL'
gmail_password = 'YOUR_PASSWORD'

for i in range(50):
    sent_from = gmail_user
    to = ['IngrahamAngle@Fox.com'] # this is the homophobic email
    subject = 'im not gay'
    body = 'Ok Im not gay but Im Swedish and I have a fantasy of Germany winning WWII and Sweden having to transport boipussy slaves and Aryan twinks to senior SS officers for fun. I imagine Im a shy blond twink with smooth pale skin whos brought into comedian Heinrichs room to please him. Hes a big, broad-shouldered weed with a jaw that could cut a diamond and big daddy muscles, and Im a skinny, pathetic kid. He pulls me into a kiss and presses my chest against his. He pushed me to the bed and ripped off my pretty virgin panties, which he had been waiting for for a long time. He teases my boipussy with his big thick German cock and then pulls out all the stops: fuck me with a power Ive never felt before. Each thrust makes him moan with pleasure. I like the fact that I give him pleasure. He penetrates deep into my Swedish cilia, slips up my asshole and then squeezes me with his mighty German man arms until I fall asleep on his chest.'
# enjoy the copypasta
    email_text = """\
    From: %s
    To: %s
    Subject: %s

    %s
    """ % (sent_from, ", ".join(to), subject, body)

    try:
        smtp_server = smtplib.SMTP_SSL('smtp.gmail.com', 465)
        smtp_server.ehlo()
        smtp_server.login(gmail_user, gmail_password)
        smtp_server.sendmail(sent_from, to, email_text)
        smtp_server.close()
        print ("Email sent successfully!")
    except Exception as ex:
        print ("Something went wrong….",ex)

# SimcomTester
Basically Dial / SMS using a Simcom Board Over TTL

Once you get the prompt: "Enter Command" you can type 3 commands:

DIAL

SMS

TEST

Anything else custom you might type is sent to the unit directly.

Remember to Modify these two lines (in the Program.cs) as appropriate:

Port.WriteLine("AT+CMGS=\"[+INTL YOUR NUMBER]\"\r");

Port.WriteLine("ATD + [+INTL YOUR NUMBER];\r");

EXIT to quit

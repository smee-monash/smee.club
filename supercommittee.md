---
permalink: /supercommittee
title: Supercommittee
---

<style>
	h1, h2 {
		text-align: center;
	}

	.profiles {
		display: flex;
		justify-content: center;
		flex-wrap: wrap;
	}

	.profiles article {
		margin: 1em;
	}

	.profiles article img {
		width: 160px;
		height: 160px;
		border-radius: 50%;
	}

	.profiles article p {
		margin: 0;
		text-align: center;
	}
</style>

# 2027 SMEE Supercommittee

{% for subcommittee in site.data.supercommittee %}

## {{ subcommittee.subcommittee }}

<div class="profiles">
	{% for member in subcommittee.directors %}
<article markdown=1>
[![Photo of {{ member.name }}]({{ member.photo | default: "./favicon.ico" }})]({{ member.link }})

{{ member.name }}

*{{ member.position }}*
</article>
	{% endfor %}
</div>
<div class="profiles">
	{% for member in subcommittee.members %}
<article markdown=1>
[![Photo of {{ member.name }}]({{ member.photo | default: "./favicon.ico" }})]({{ member.link }})

{{ member.name }}

*{{ member.position }}*
</article>
	{% endfor %}
</div>
{% endfor %}

# Past committees

May be incomplete.

2026  
President						Nhan Nguyen  
Vice President						Timmy Hess  
Treasurer						Amiru Peeli Kumburage  
Secretary						Sophie Li  
Industry Director					Steph Koutsimpiris  
Events Director					Hugo Knights-Burke, Sophie Windust  
Marketing Director					Satria Hadiwijaya, Arthur Nguyen  
Fourth Year Representative				Leonie Chim  
Third Year Representative				Erin Holland, Christopher Burton  
Second Year Representative				Om Patel  
First Year Representative				Sayuni Perera  
Post-Graduate Representative			Oliver Hoy, Arthur Nguyen, Trajco Nikolov

2025  
President						Lacie Nguyen  
Vice President						Riley Cheung  
Treasurer						Leonie Chim  
Secretary						Nhan Nguyen  
Industry Director					Aiden Doak  
Events Director					Evyn Bermingham  
Marketing Director					Elliott Varasdi, Ihsan Imran  
Fourth Year Representative				Oliver Hoy  
Third Year Representative				Orlando Chamberlain  
Second Year Representative				Zali Peet  
First Year Representative				Sophie Li  
Post-Graduate Representative			Hiten Garg

2024  
President						Anantyash Dixit  
Vice President						Lacie Nguyen  
Treasurer						Oliver Hoy  
Secretary						Nhan Nguyen  
Careers and Sponsorships Representative		Yann Fiedler  
Events Manager					Sid Iyer  
Marketing Manager					Dylan Kumar  
Fourth Year Representative				Rachel Coker  
Third Year Representative				Aarushi Raheja  
Second Year Representative				Leonie Chim  
First Year Representative				Elliott Varasdi  
Post-Graduate Representative			Hiten Garg

2023  
President						Isuru Peiris  
Vice President						Aarushi Raheja  
Treasurer						Brandon Khim  
Secretary						Wu-Wei Li  
Careers and Sponsorship Representative		Sam McMahon  
Events Manager					Borui Li, Dylan Kumar  
Marketing Manager					Nhan Nguyen  
Fourth Year Representative				Riley Cheung  
Third Year Representative				Arjuna Sanjayan  
Second Year Representative				Lacie Nguyen  
First Year Representative				Leonie Chim

2022  
President						Harrison Broadbent  
Vice President						Surya Kannan, Isuru Peiris  
Treasurer						Emily Jap  
Secretary						Shaf Haque Shadman  
Careers and Sponsorship Representative		Isuru Peiris, Borui Li  
Events Representative				Brandon Khim  
Third Year Representative				Mub Murshed  
Second Year Representative				Aryaman Kathuria, Aarushi Raheja

2021  
President						Emma Scully  
Vice President						Callum Wearne  
Treasurer						Yasir Sultani  
Secretary						Liz Chai  
Careers and Sponsorship Representative		Surya Kannan  
Events Representative				Mathen Jose, Emily Jap  
Fourth Year Representative				Minsoo Kim  
Third Year Representative				Geordie McClelland  
Second Year Representative				Harrison Broadbent

2020  
President						Quentin Ngai  
Vice President						Stephen Bajan  
Treasurer						Yasir Sultani  
Secretary						Emma Scully  
Careers and Sponsorship Representative		Sukhjinder Singh  
Events Representative				Cameron Mullis  
Fourth Year Representative				Rory Sutherland  
Third Year Representative				Callum Wearne

2019  
President						Matthew Seymour  
Vice President						Joshua Smith, Quentin Ngai  
Treasurer						David Inguanti  
Secretary						Elie Loummer  
Careers and Sponsorship Representative		Kuan Hou Angus Lee  
Events Representative				Anna Harvey  
Fourth Year Representative				Stephen Bajan  
Third Year Representative				Quentin Ngai, Kevin Chen, Emma Scully  
Second Year Representative				Yas Ye

2018  
President						Matthew Timms  
Vice President						Amy Prentice  
Treasurer						Rory Sutherland, David Inguanti  
Secretary						Matthew Seymour  
Careers and Sponsorship Representative		Elie Loummer  
Events Representative				Patrick Graham  
Fourth Year Representative				Kuan Hou Angus Lee  
Third Year Representative				Adnaan Sayed  
Second Year Representative				David Inguanti, Liz Chai

2017  
President						Lucina Togno  
Vice President						Antoine Genesi  
Treasurer						Rory Sutherland  
Secretary						Matthew Timms  
Careers and Sponsorship Representative		Daniel Smith  
Events Representative				Will Donohoe  
Fourth Year Representative				Lachlan Smith  
Third Year Representative				Matthew Seymour  
Second Year Representative				Anita Karapanos

2016  
President						Lucina Togno  
Vice President						Tom Merry  
Treasurer						Merlin Okle  
Secretary						Luke Ditria  
Careers and Sponsorship Representative		Daniel Smith  
Events Representative				Matthew Timms  
Fourth Year Representative				Peter Bell  
Third Year Representative				Will Donohoe  
Second Year Representative				Rory Sutherland

2015  
President						Jonathon Geeves  
Vice President						Vincent Leung  
Treasurer						Lucina Togno  
Secretary						David Stojanovski  
Careers and Sponsorship Representative		Tom Merry  
Events Representative				Joshua Weberruss  
Fourth Year Representative				Craig van Dort  
Third Year Representative				Alex Muir  
Second Year Representative				Julia Kowalska

2014  
President						Jonathon Geeves  
Vice President						Vincent Leung  
Treasurer						David Stojanovski  
Secretary						Sahil Bhasin  
Careers and Sponsorship Representative		Ray Tinney  
Events Representative				Sabina Dabkowski-Chandler  
Fourth Year Representative				Anthony Day  
Third Year Representative				Ashley Schuurman  
Second Year Representative				Lucina Togno

2013  
President						Jamila Bird  
Vice President						Louise Stroyov  
Treasurer						Brendan Wreford  
Secretary						Tim Lacey  
Special Events Representative			Jonathon Geeves  
Fourth Year Representative				Ben Ebsworth  
Third Year Representative				Anthony Day  
Second Year Representative				Angus Smith  
General Representative				Jarman Stephens, Kurt Mejak, Jakob van Hest, Ryan Jennings, Charles Morley, Joe Feng

2012  
President						Meili Castaldi, Louise Stroyov  
Vice President						Sam Trolland, Kurt Mejak  
Treasurer						Keith Matthies  
Secretary						Louise Stroyov, Joe Feng  
Special Event Representative			Jamila Bird  
Fourth Year Representative				Whye Leon Seng  
Third Year Representative				Gail Schwartz, Anthony Day  
Second Year Representative				Kurt Mejak, Luan Nguyen  
Project Representative				Damien Anthony  
Marketing Representative				Joe Feng  
IT Representative					Tim Lacey  
General Representative				Dayn Orwin, Eugene Lee, Paul Grey, Jakob van Hest, Ray Tinney, Namita Doshi, Ryan Jennings

2011  
President						Nevhan Ramadan  
Vice President						Meng Wang  
Treasurer						Keith Matthies  
Secretary						Adam Harris  
Special Event Representative			Manish Pahwa  
Fourth Year Representative				Gidon Cain  
Third Year Representative				Michael Nguyen  
General Representative				Dayn Orwin, Brendan Li, Meili Castaldi, Joe Humphries, Matt Birman

2010  
President						Lizzie Anderson  
Vice President						Will Robertson  
Treasurer						Jay Sempio  
Secretary						Meng Wang  
Special Events Representative			Jordan Guest  
Second Year Representative				Michael Nguyen  
General Representative				Jonathan Ross, Leon Childs, Luke Koedijk, Patrick Lenaghan

2009  
President						Rory

2008

2007

2006  
President						Jervis Whitley  
Treasurer						Yarlini Amirthanesan  
Secretary						Rowan Doherty  
Fourth Year Representative				Feven Getachew  
Third Year Representative				Karl Urdevics  
Second Year Representative				Uma Amirthanesan  
Sports Representative				Carolyn Tiet  
General Representative				Mirza Saric, Meagan Soutter  
IEE Representative					Stephen Backway

2005  
President						Graham Wilkinson  
Treasurer						Alex Chen  
Secretary						Ian Latimour  
Fourth Year Representative				Tom  
Third Year Representative				Feven Getachew  
Second Year Representative				Mirza Saric  
Sports Representative				Rowan Doherty  
IEE Representative					Wang  
General Representative				Yarlini Arnirtharesan, Stephen Backway

2004  
President						Megan Sutherland  
Treasurer						Gin Cullinan  
Secretary						Graham Wilkinson  
Fourth Year Representative				Aidan Crees  
Third Year Representative				Nigel Zeinert, David Ots  
Sports Representative				Cromwel Flores  
General Representative				Jason Pollock, Marcus Nation, Guillaume Geoffroy

2003  
President						Robert Brett  
Treasurer						Rachel Bertucci  
Secretary						Amber Garrett  
Fourth Year Representative				Jason Pollock  
Third Year Representative				Gin Cullinan  
Second Year Representative				Nick Kennedy  
Sports Representative				Graham Wilkinson  
General Representative				Megan Sutherland, Mark Wexler, Robert Duca

2002  
President						Paul Siegemund  
Treasurer						Oliver Hsieh  
Secretary						Hugh Torresan, Bruno Valenta  
Sponsorship Representative				Fiona Muller  
Sports Representative				Kjell Schwab  
Fourth Year Representative				Bruno Valenta  
Third Year Representative				Mark Wexler, Megan Sutherland  
Second Year Representative				Arron Drew  
Web Designer						Hayley Cronin  
Promotions Representative				Robert Brett  
General Representative				Eric Ellis

2001  
President						Kate Worland, Fiona Muller  
Treasurer						Paul Siegemund  
Secretary						Hugh Torresan  
Fourth Year Representative				Robert Brett  
Second Year Representative				Amber Garrett  
General Representative				Alicia Holmes, Eric Ellis

2000

1999

1998

1997  
President						Geoff Popper  
Treasurer						Nick  
Secretary						Zoe Pleasants  
Fourth Year Committee Member			Burke Lau  
Fourth Year Representative				Ewen Christopher  
Third Year Committee Member			Sam Fyfield  
Third Year Representative				Luke  
Committee Member					Nick Wadsley

1996

1995

1994  
President						Louise Ninio  
Treasurer						Shane Reynolds  
Secretary						John Sawaya  
Fourth Year Representative				Dave Redman  
Third Year Representative				Ira Makdessian  
Post-Graduate Representative			Andrew Kotsopoulos  
Committee Member					David Lapsley, Nick McKinley, Lou Giorlando, Despina Salagaras, Jagir Baxi  
Immediate Past President				Debbie Larkin

1993  
President						Debbie Larkin  
Vice President						Ian Fuller  
Second Year Representative				Mark Osborne  
Committee Member					Dave Redman, Louise Ninio, Richard DeFelice, Arthur Giannakis, Mat Pittok, Phil Curtis, John Sawaya, Stephen Handley, Ioannis Psallidas, Daniel Zmood

1992  
President						Gene Seenyan  
Vice President						Gavan Turner  
Treasurer						Sam Tasdelen  
Secretary						Kevin Leverment  
Fourth Year Representative				Ian Fuller  
Third Year Representative				Phil Curtis  
Member Without Portfolio				Debbie Larkin, Geoff W.

1991  
President						Garry Starr  
Vice President						Jamie Nicholls  
Treasurer						Gene Seenyan  
Secretary						Gavan Turner  
Fourth Year Representative				Alan Trembleau  
Third Year Representative				Peter Schmidt  
Member Without Portfolio				Roger Loh, J. Waterstone, J. Chard

1990  
President						Michael Ham  
Vice President						Andrew Leong  
Treasurer						Greg Robinson  
Secretary						Chris Betts  
Assistant Secretary					Tharshan V.  
Deputy Treasurer					Anu Rao  
Fourth Year Representative				Lim Song Yam  
Third Year Representative				Janto Lim  
Second Year Representative				Debbie Larkin  
Editor							Chris Chan

1989  
Treasurer						Karen Handreck  
Third Year Representative				Lim Song Yam  
Committee Member					David Lewis

1988  
President						Lasha Aponso  
Vice President						Gary Ruben  
Treasurer						Cathie Overberg  
Secretary						Karen Handreck  
Fourth Year Representative				David Lewis, Katherine Fisher, Daljinder Singh  
Third Year Representative				Simon Ryan, David Lewis  
Second Year Representative				Chris Chan, Lim Song Yam  
First Year Representative				Misha Vesplak

1987  
President						James Renwick  
Vice President						Donna Lai  
Treasurer						Steven Ryan  
Secretary						Bernie O’Brien  
Fourth Year Representative				Chris Walsh  
Third Year Representative				Simon Ryan

1986  
President						Adam Crow  
Vice President						John Hall  
Treasurer						Daniel Grimm  
Secretary						Kevin Payne  
Fourth Year Representative				David Boschma  
Third Year Representative				Ken Messner, James Renwick  
Second Year Representative				Simon Ryan

1985  
President						Warwick Slade  
Treasurer						Jeff Ferdinands  
Secretary						Antony Braakhuis  
Fourth Year Representative				Jonathon Clyne  
Third Year Representative				Adam Crow  
Second Year Representative				Marie Farrar

1984  
President						Jon Retford  
Treasurer						Greg Burgio  
Secretary						Antony Braakhuis  
Fourth Year Representative				James Wiles  
Third Year Representative				Richard Potter  
Second Year Representative				Adam Crow

1983  
President						Peter Feder  
Treasurer						Greg Burgio  
Secretary						Ralph Youie  
Fourth Year Representative				Adrian Brooks  
Third Year Representative				Jon Retford  
Second Year Representative				Antony Braakhuis

1982  
President						Brett Rogers  
Vice President						Rob Miller  
Secretary						Anthony Llewelyn  
Treasurer						Steve Beyer  
Fourth Year Representative				Greg Brown  
Third Year Representative				Adrian Brooks  
Second Year Representative				Adrian Inch

1981  
President						Geoff Ramadan  
Vice President						Robert Broomfield  
Treasurer						Alan Gorick  
Secretary						Wong C.Y.  
Fourth Year Representative				Goh H.P.

1980

1979

1978  
President						Colin Hales  
Secretary						David Hurley

1977  
President						Paul Felsbourg  
Treasurer						Jim Reynolds  
Secretary						Collin McAndrew

1976  
President						Henk Van Hoek  
Treasurer						David Atkinson  
Secretary						Brian Drummond, R. Hillis

1975  
President						Peter Hart  
Treasurer						Ian Spence  
Secretary						Alan Conduit

1974  
President						Harry Bhuta  
Treasurer						Brian Little  
Secretary						David Miles

1973  
President						Leo Wursthorn  
Treasurer						Peter Harrison  
Secretary						Ian Cook

1972  
President						P. Pain  
Treasurer						J. Teal  
Secretary						G. Sleer

1962-1971
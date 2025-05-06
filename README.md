# cs1009-homework-1-data-collection---web-scraping---data-parsing-solved
**TO GET THIS SOLUTION VISIT:** [CS1009 Homework 1-Data Collection – Web Scraping – Data Parsing Solved](https://www.ankitcodinghub.com/product/cs1009-homework-1-data-collection-web-scraping-data-parsing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;55238&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1009 Homework 1-Data Collection - Web Scraping - Data Parsing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this homework, your goal is to learn how to acquire, parse, clean, and analyze data. Initially you read the data from a file, then you scrape them directly from a website. You look for specific pieces of information by parsing the data, you clean the data to prepare them for analysis, and finally, you answer some questions.

Part A Help a professor convert his publications to bibTex

Overview

In Part 1 your goal is to parse the HTML page of a Professor containing some of his publications, and answer some questions. This page is provided to you in the file data/publist_super_clean.html . There are 44 publications in descending order from No. 244 to No. 200.

You are to use python’s regular expressions, a powerful way of parsing text. You may not use any parsing tool such as Beautiful Soup yet. In doing so you will get more familiar with three of the common file formats for storing and transferring data, which are:

CSV, a text-based file format used for storing tabular data that are separated by some delimiter, usually comma or space.

HTML/XML, the stuff the web is made of.

JavaScript Object Notation(JSON), a text-based open standard designed for transmitting structured data over the web.

Question 1: Parsing using Regular Expressions

1.1 Write a function called get_pubs that takes a .html filename as an input and returns a string containing the HTML page in this file (see definition below). Call this function using data/publist_super_clean.html as input and name the returned string prof_pubs .

1.2 Calculate how many times the author named ‘ C.M. Friend ‘ appears in the list of publications.

1.3 Find all unique journals and copy them in a variable named journals .

1.4 Create a list named pub_authors whose elements are strings containing the authors’ names for each paper.

Hints

Look for patterns in the HTML tags that reveal where each piece of information such as the title of the paper, the names of the authors, the journal name, is stored. For example, you might notice that the journal name(s) is contained between the &lt;I&gt; HTML tag.

Each publication has multiple authors.

C.M. Friend also shows up as Cynthia M. Friend in the file. Count just C. M. Friend .

There is a comma at the end of the string of authors. You can choose to keep it in the string or remove it and put it back when you write the string as a BibTex entry.

You want to remove duplicates from the list of journals.

Resources

Regular expressions: a) https://docs.python.org/3.3/library/re.html

(https://docs.python.org/3.3/library/re.html), b) https://regexone.com (https://regexone.com), and c) https://docs.python.org/3/howto/regex.html (https://docs.python.org/3/howto/regex.html).

** HTML:** if you are not familiar with HTML see https://www.w3schools.com/html/ (https://www.w3schools.com/html/) or one of the many tutorials on the internet.

** Document Object Model (DOM):** for more on this programming interface for HTML and XML documents see https://www.w3schools.com/js/js_htmldom.asp (https://www.w3schools.com/js/js_htmldom.asp).

1.1

In [2]:

In [3]:

You should see an HTML page

&lt;LI&gt;

&lt;A HREF=”Papers/2011/PhysRevB_84_125411_2011.pdf” target=”paper244″&gt; &amp;quot;Approaching the intrinsic band gap in suspended high-mobility graphen e nanoribbons&amp;quot;&lt;/A&gt;

&lt;BR&gt;Ming-Wei Lin, Cheng Ling, Luis A. Agapito, Nicholas Kioussis, Yiyang Zh ang, Mark Ming-Cheng Cheng,

&lt;I&gt;PHYSICAL REVIEW B &lt;/I&gt; &lt;b&gt;84&lt;/b&gt;, 125411 (2011)

&lt;BR&gt;

&lt;/LI&gt;

&lt;/OL&gt;

&lt;OL START=243&gt;

&lt;LI&gt;

&lt;A HREF=”Papers/2011/PhysRevB_84_035325_2011.pdf” target=”paper243″&gt; &amp;quot;Effect of symmetry breaking on the optical absorption of semiconducto r nanoparticles&amp;quot;&lt;/A&gt;

&lt;BR&gt;JAdam Gali, Efthimios Kaxiras, Gergely T. Zimanyi, Sheng Meng,

&lt;I&gt;PHYSICAL REVIEW B &lt;/I&gt; &lt;b&gt;84&lt;/b&gt;, 035325 (2011)

&lt;BR&gt;

&lt;/LI&gt;

&lt;/OL&gt;

&lt;OL START=242&gt;

&lt;LI&gt;

&lt;A HREF=”Papers/2011/PhysRevB_83_054204_2011.pdf” target=”paper242″&gt; &amp;quot;Influence of CH2 content and network defects on the elastic propertie s of organosilicate glasses&amp;quot;&lt;/A&gt;

&lt;BR&gt;Jan M. Knaup, Han Li, Joost J. Vlassak, and Efthimios Kaxiras,

&lt;I&gt;PHYSICAL REVIEW B &lt;/I&gt; &lt;b&gt;83&lt;/b&gt;, 054204 (2011)

&lt;BR&gt;

&lt;/LI&gt;

&lt;/OL&gt;

1.2

In [6]:

5

1.3

In [7]:

Your output should look like this (remember, no duplicates):

‘ACSNano.’,

‘Ab initio’,

‘Ab-initio’,

‘Acta Mater.’,

‘Acta Materialia’,

‘Appl. Phys. Lett.’,

‘Applied Surface Science’,

‘Biophysical J.’,

‘Biosensing Using Nanomaterials’, …

‘Solid State Physics’,

‘Superlattices and Microstructures’,

‘Surf. Sci.’,

‘Surf. Sci. Lett.’,

‘Surface Science’,

‘Surface Review and Letters’,

‘Surface Sci. Lett.’,

‘Surface Science Lett.’,

‘Thin Solid Films’,

‘Top. Catal.’, ‘Z’}

1.4

[9]:

In [10]:

1 # check your code: print the list of strings containing the author(s)’ names 2 for item in pub_authors:

3 print (item)

A. Gali and E. Kaxiras,

A. Gali, E. Janzen, P. Deak, G. Kresse and E. Kaxiras,

A. Peters, S. Melchionna, E. Kaxiras, J. Latt, J. Sircar, S. Succi, Bingjun Xu, Jan Haubrich, Thomas A. Baker, Efthimios Kaxiras, and Cy nthia M. Friend,

C.E. Lekka, J. Ren, S. Meng and E. Kaxiras,

C.L. Chang, S.K.R.S. Sankaranarayanan, D. Ruzmetov, M.H. Engelhard,

E. Kaxiras and S. Ramanathan,

E. Kaxiras and S. Succi,

E. Manousakis, J. Ren, S. Meng and E. Kaxiras,

E.M. Kotsalis, J.H. Walther, E. Kaxiras and P. Koumoutsakos, F.J. Rybicki, S. Melchionna, D. Mitsouras, A.U. Coskun, A.G. Whitmor e, E. Kaxiras, S. Succi, P.H. Stone and C.L. Feldman,

H. Chen, W.G. Zhu, E. Kaxiras, and Z.Y. Zhang,

H. Li, J.M. Knaup, E. Kaxiras and J.J. Vlassak,

H.P. Chen, R.K. Kalia, E. Kaxiras, G. Lu, A. Nakano, K. Nomura,

J R Maze, A Gali, E Togan, Y Chu, A Trifonov,

J. Ren, E. Kaxiras and S. Meng,

JAdam Gali, Efthimios Kaxiras, Gergely T. Zimanyi, Sheng Meng,

Jan Haubrich Efthimios Kaxiras and Cynthia M Friend

Your output should look like this (a line for each paper’s author(s) string, with or without the comma)

S. Meng and E. Kaxiras,

G. Lu and E. Kaxiras, E. Kaxiras and S. Yip,

…

Simone Melchionna, Efthimios Kaxiras, Massimo Bernaschi and Sauro Succi,

J R Maze, A Gali, E Togan, Y Chu, A Trifonov,

E Kaxiras, and M D Lukin,

Question 2: Parsing and Converting to bibTex using Beautiful Soup

A lot of the bibliographic and publication information is displayed in various websites in a not-so-structured HTML files. Some publishers prefer to store and transmit this information in a .bibTex file which has the following format:

@article { _number_ author = John Doyle

title = Interaction between atoms URL = Papers/PhysRevB_81_085406_2010.pdf journal = Phys. Rev. B volume = 81

}

@article

{ author = Ming-Wei Lin, Cheng Ling, Luis A. Agapito, Nicholas Kioussis,

Yiyang Zhang, Mark Ming-Cheng Cheng title = “Approaching the intrinsic band gap in suspended high-mobility

graphene nanoribbons”

URL = Papers/2011/PhysRevB_84_125411_2011.pdf journal = PHYSICAL REVIEW B volume = 84

}

About the bibTex format (http://www.bibtex.org).

In Question 2 you are given an .html file containing a list of papers scraped from the author’s website and you are to write the information into .bibTex format. We used regular expressions for parsing HTML in the previous question but just regular expressions are hard to use in parsing real-life websites. A useful tool is

[BeautifulSoup] (http://www.crummy.com/software/BeautifulSoup/

(http://www.crummy.com/software/BeautifulSoup/)) (BS). You will parse the same file, this time using BS, which makes parsing HTML a lot easier.

2.1 Write a function called make_soup that accepts a filename for an HTML file and returns a BS object.

2.2 Write a function that reads in the BS object, parses it, converts it into the .bibTex format using python string manipulation and regular expressions, and writes the data into publist.bib . You will need to create that file in your folder.

HINT

Inspect the HTML code for tags that indicate information chunks such as title of the paper. You had already done this in Part 1 when you figured out how to get the name of the journal from the HTML code.

The find_all method of BeautifulSoup might be useful.

Question 2.2 is better handled if you break the code into functions, each performing a small task such as finding the author(s) for each paper.

Make sure you catch exceptions when needed.

Regular expressions are a great tool for string manipulation.

Resources

BeautifulSoup Tutorial (https://www.dataquest.io/blog/web-scraping-tutorial-python/).

More about the BibTex format (http://www.bibtex.org).

2.1

1 # check your code: print the Beautiful Soup object, you should see an HTML page 2 print(soup)

&lt;!DOCTYPE HTML PUBLIC “-//W3C//DTD HTML 4.01 Transitional//EN” “htt p://www.w3.org/TR/html4/loose.dtd”&gt;

&lt;html&gt;&lt;head&gt;&lt;title&gt;Kaxiras E journal publications&lt;/title&gt;

&lt;meta content=”text/html;charset=utf-8″ http-equiv=”Content-Type”/&gt; &lt;link href=”../styles/style_pubs.css” rel=”stylesheet” type=”text/cs s”/&gt;

&lt;meta content=”” name=”description”/&gt;

&lt;meta content=”Kaxiras E, Multiscale Methods, Computational Material s” name=”keywords”/&gt; &lt;/head&gt;&lt;body&gt;

&lt;ol start=”244″&gt;

&lt;li&gt;

&lt;a href=”Papers/2011/PhysRevB_84_125411_2011.pdf” target=”paper244″&gt; “Approaching the intrinsic band gap in suspended high-mobility graph ene nanoribbons”&lt;/a&gt;

&lt;br/&gt;Ming-Wei Lin, Cheng Ling, Luis A. Agapito, Nicholas Kioussis, Y iyang Zhang, Mark Ming-Cheng Cheng,

&lt;i&gt;PHYSICAL REVIEW B &lt;/i&gt; &lt;b&gt;84&lt;/b&gt;, 125411 (2011)

&lt;br/&gt; &lt;/li&gt;

Your output should look like this:

&lt;!DOCTYPE HTML PUBLIC “-//W3C//DTD HTML 4.01 Transitional//EN” “http://www.w3.org/TR/html4/loose.dtd”&gt;

&lt;title&gt;Kaxiras E journal publications&lt;/title&gt;

&lt;head&gt;

&lt;meta content=”text/html;charset=utf-8″ http-equiv=”Content-Type”/&gt;

&lt;link href=”../styles/style_pubs.css” rel=”stylesheet” type=”text/css”/&gt;

&lt;meta content=”” name=”description”/&gt;

&lt;meta content=”Kaxiras E, Multiscale Methods, Computational Materials” name

=”keywords”/&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;ol start=”244″&gt;

&lt;li&gt;

&lt;a href=”Papers/2011/PhysRevB_84_125411_2011.pdf” target=”paper244″&gt; “Approaching the intrinsic band gap in suspended high-mobility graphene nan oribbons”&lt;/a&gt;

&lt;br/&gt;Ming-Wei Lin, Cheng Ling, Luis A. Agapito, Nicholas Kioussis, Yiyang Z hang, Mark Ming-Cheng Cheng,

&lt;i&gt;PHYSICAL REVIEW B &lt;/i&gt; &lt;b&gt;84&lt;/b&gt;, 125411 (2011)

&lt;br/&gt;

&lt;/li&gt;

&lt;/ol&gt;

&lt;ol start=”243″&gt;

&lt;li&gt;

&lt;a href=”Papers/2011/PhysRevB_84_035325_2011.pdf” target=”paper243″&gt; “Effect of symmetry breaking on the optical absorption of semiconductor nan oparticles”&lt;/a&gt;

&lt;br/&gt;JAdam Gali, Efthimios Kaxiras, Gergely T. Zimanyi, Sheng Meng,

&lt;i&gt;PHYSICAL REVIEW B &lt;/i&gt; &lt;b&gt;84&lt;/b&gt;, 035325 (2011)

&lt;br/&gt;

&lt;/li&gt;

&lt;/ol&gt; …

2.2

Your output should look like this

@article

{ author = Ming-Wei Lin, Cheng Ling, Luis A. Agapito, Nicholas Kioussis,

Yiyang Zhang, Mark Ming-Cheng Cheng title = “Approaching the intrinsic band gap in suspended high-mobility

graphene nanoribbons”

URL = Papers/2011/PhysRevB_84_125411_2011.pdf journal = PHYSICAL REVIEW B volume = 84

}

…

@article

{ author = E. Kaxiras and S. Succi title = “Multiscale simulations of complex systems: computation meets reality”

URL = Papers/SciModSim_15_59_2008.pdf journal = Sci. Model. Simul.

volume = 15

}

@article

{ author = E. Manousakis, J. Ren, S. Meng and E. Kaxiras title = “Effective Hamiltonian for FeAs-based superconductors” URL = Papers/PhysRevB_78_205112_2008.pdf journal = Phys. Rev. B volume = 78

}

Part B: Follow the stars in IMDb’s list of “The Top 100 Stars for 2017”

Overview

In Part 3 your goal is to extract information from IMDb’s Top 100 Stars for 2017

(https://www.imdb.com/list/ls025814950/ (https://www.imdb.com/list/ls025814950/)) and perform some analysis on each star in the list. In particular we are interested to know: a) how many performers made their first movie at 17? b) how many performers started as child actors? c) who is the most proliferate actress or actor in IMDb’s list of the Top 100 Stars for 2017? . These questions are addressed in more details in the Questions below.

When data is not given to us in a file, we need to fetch them using one of the following ways:

download a file from a source URL query a database query a web API

scrape data from the web page

Question 1: Web Scraping Using Beautiful Soup

1.1 Download the webpage of the “Top 100 Stars for 2017″ (https://www.imdb.com/list/ls025814950/

(https://www.imdb.com/list/ls025814950/)) into a requests object and name it my_page . Explain what the following attributes are:

my_page.text , my_page.status_code , my_page.content .

1.2 Create a Beautiful Soup object named star_soup giving my_page as input.

1.3 Write a function called parse_stars that accepts star_soup as its input and generates a list of dictionaries named starlist (see definition below). One of the fields of this dictionary is the url of each star’s individual page, which you need to scrape and save the contents in the page field. Note that there is a ton of information about each star on these webpages.

1.4 Write a function called create_star_table to extract information about each star (see function definition for the exact information to extract). Only extract information from the first box on each star’s page. If the first box is acting, consider only acting credits and the star’s acting debut, if the first box is Directing, consider only directing credits and directorial debut.

1.5 Now that you have scraped all the info you need, it’s a good practice to save the last data structure you created to disk. That way if you need to re-run from here, you don’t need to redo all these requests and parsing.

Save this information to a JSON file and submit this JSON file in Canvas with your notebook.

1.6 Import the contents of the teaching staff’s JSON file ( data/staff_starinfo.json ) into a pandas dataframe. Check the types of variables in each column and clean these variables if needed. Add a new column to your dataframe with the age of each actor when they made first movie (name this column age_at_first_movie ).

1.7 You are now ready to answer the following intriguing questions:

How many performers made their first movie at 17?

How many performers started as child actors? Define child actor as a person less than 12 years old.

Who is the most prolific actress or actor in IMDb’s list of the Top 100 Stars for 2017?

1.8 Make a plot of the number of credits versus the name of actor/actress.

Hints

Create a variable that groups actors/actresses by the age of their first movie. Use pandas’ .groupby to divide the dataframe into groups of performers that for example started performing as children (age &lt; 12). The grouped variable is a GroupBy pandas object and this object has all of the information needed to then apply some operation to each of the groups.

When cleaning the data make sure the variables with which you are performing calculations are in numerical format.

The column with the year has some values that are double, e.g. ‘2000-2001′ and the column with age has some empty cells. You need to deal with these before performing calculations on the data!

You should include both movies and TV shows.

Resources

The requests library makes working with HTTP requests powerful and easy. For more on the requests library see http://docs.python-requests.org/ (http://docs.python-requests.org/)

[16]:

1.1

In [17]:

200

In [31]:

1 print(my_page.content)

b’\n\n\n\n&lt;!DOCTYPE html&gt;\n&lt;html\n xmlns:og=”http://ogp.me/ns#”\n xmlns:fb=”http://www.facebook.com/2008/fbml”&gt;\n &lt;head&gt;\n \n &lt;meta charset=”utf-8″&gt;\n &lt;meta http-equiv=”X-UA-Com patible” content=”IE=edge”&gt;\n\n &lt;meta name=”apple-itunes-app” con tent=”app-id=342792525, app-argument=imdb:///list/ls025814950?src=md ot”&gt;\n\n\n\n &lt;script type=”text/javascript”&gt;var IMDbTimer={st arttime: new Date().getTime(),pt:\’java\’};&lt;/script&gt;\n\n&lt;script&gt;\n if (typeof uet == \’function\’) {\n uet(“bb”, “LoadTitle”, {wb: 1});\n }\n&lt;/script&gt;\n &lt;script&gt;(function(t){ (t.events = t.events

|| {})[“csm_head_pre_title”] = new Date().getTime(); })(IMDbTimer);

&lt;/script&gt;\n &lt;title&gt;Top 100 Stars of 2017 – IMDb&lt;/title&gt;\n &lt;s cript&gt;(function(t){ (t.events = t.events || {})[“csm_head_post_titl e”] = new Date().getTime(); })(IMDbTimer);&lt;/script&gt;\n&lt;script&gt;\n i f (typeof uet == \’function\’) {\n uet(“be”, “LoadTitle”, {wb: 1});\n }\n&lt;/script&gt;\n&lt;script&gt;\n if (typeof uex == \’function

\’) {\n uex(“ld”, “LoadTitle”, {wb: 1});\n }\n&lt;/script&gt;\n\n

&lt;link rel=”canonical” href=”https://www.imdb.com/list/ls025814950/” /&gt;\n &lt;meta property=”og:url” content=”http://www.imdb.com/lis t/ls025814950/” /&gt;\n\n&lt;script&gt;\n if (typeof uet == \’function\’)

{\n uet(“bb” “LoadIcons” {wb: 1});\n }\n&lt;/script&gt;\n &lt;scri

1.2

In [32]:

[33]:

1 # check your code – you should see an HTML page

2 print (star_soup.prettify()[:])

&lt;!DOCTYPE html&gt;

&lt;html xmlns:fb=”http://www.facebook.com/2008/fbml” xmlns:og=”http:// ogp.me/ns#”&gt;

&lt;head&gt;

&lt;meta charset=”utf-8″/&gt;

&lt;meta content=”IE=edge” http-equiv=”X-UA-Compatible”/&gt;

&lt;meta content=”app-id=342792525, app-argument=imdb:///list/ls02581

4950?src=mdot” name=”apple-itunes-app”/&gt;

&lt;script type=”text/javascript”&gt;

var IMDbTimer={starttime: new Date().getTime(),pt:’java’};

&lt;/script&gt; &lt;script&gt;

if (typeof uet == ‘function’) { uet(“bb”, “LoadTitle”, {wb: 1});

}

&lt;/script&gt;

&lt;script&gt;

(function(t){ (t.events = t.events || {})[“csm_head_pre_title”] = new Date().getTime(); })(IMDbTimer); &lt;/script&gt;

1.3

Function ——– parse_stars

Input ——

star_soup: the soup object with the scraped page

Returns ——- a list of dictionaries; each dictionary corresponds to a star profile and h as the following data:

name: the name of the actor/actress as it appears at the top gender: 0 or 1: translate the word ‘actress’ into 1 and ‘actor’ into

‘0’ url: the url of the link under their name that leads to a page with det

ails

page: the string containing the soup of the text in their individual in

fo page (from url)

Example:

——–

{‘name’: Tom Hardy,

‘gender’: 0,

‘url’: https://www.imdb.com/name/nm0362766/?ref_=nmls_hd,

‘page’: BS object with ‘html text acquired by scraping the ‘url’ page’

}

In [176]:

1 # your code here

2 import time

3 from tqdm import tqdm

4

5 def parse_stars(star_soup):

6 actors = star_soup.find_all(‘div’, {‘class’: ‘lister-item mode-detail’})

7 starlist = []

8 for actor in tqdm(actors):

9 star = {}

10 name = re.findall(

11 ‘&lt;a href=”/name/.+”&gt;(.[\w].*)’,

12 str(actor)

13 )[0].strip()

14 star.update({‘name’: name})

15 gender = 1

16 if ‘Actor’ in str(actor.find_all(‘p’)[0]):

17 gender = 0

18 star.update({‘gender’: gender})

19 url = ‘https://www.imdb.com’ 20 url += re.findall(‘&lt;a href=”(/name/.+)”&gt;.[\w].*’,str(actor))[0]

21 star.update({‘url’: url})

22 page = requests.get(url)

23 time.sleep(np.random.randint(8, 12))

24 page = BeautifulSoup(page.content)

25 star.update({‘page’: page})

26 starlist.append(star)

27 return starlist

28

29 starlist = parse_stars(star_soup)

100%|██████████| 100/100 [19:38&lt;00:00, 11.79s/it]

Your output should look like this:

{‘name’: ‘Gal Gadot’,

‘gender’: 1,

‘url’: ‘https://www.imdb.com/name/nm2933757?ref_=nmls_hd’,

‘page’:

&lt;!DOCTYPE html&gt;

&lt;html xmlns:fb=”http://www.facebook.com/2008/fbml” xmlns:og=”http://ogp.m e/ns#”&gt;

&lt;head&gt;

&lt;meta charset=”utf-8″/&gt;

&lt;meta content=”IE=edge” http-equiv=”X-UA-Compatible”/&gt;

&lt;meta content=”app-id=342792525, app-argument=imdb:///name/nm2933757?src=m dot” name=”apple-itunes-app”/&gt;

&lt;script type=”text/javascript”&gt;var IMDbTimer={starttime: new Date().getTim e(),pt:’java’};&lt;/script&gt;

&lt;script&gt;

if (typeof uet == ‘function’) { uet(“bb”, “LoadTitle”, {wb: 1});

}

&lt;/script&gt;

&lt;script&gt;(function(t){ (t.events = t.events || {})[“csm_head_pre_title”] = new Date().getTime(); })(IMDbTimer);&lt;/script&gt;

…

1.4

Function ——– create_star_table

Input —— the starlist

Returns ——-

a list of dictionaries; each dictionary corresponds to a star profile and h as the following data:

star_name: the name of the actor/actress as it appears at the top gender: 0 or 1 (1 for ‘actress’ and 0 for ‘actor’) year_born : year they were born first_movie: title of their first movie or TV show year_first_movie: the year they made their first movie or TV show credits: number of movies or TV shows they have made in their career.

——– Example:

{‘star_name’: Tom Hardy,

‘gender’: 0,

‘year_born’: 1997,

‘first_movie’ : ‘Batman’,

‘year_first_movie’ : 2017,

‘credits’ : 24}

[217]:

1 # your code here

2

3 def create_star_table(starlist: list) -&gt; list:

4 star_table = []

5 for actor in tqdm(starlist):

6 star = {}

7 star.update({‘star_name’: actor[‘name’]})

8 star.update({‘gender’: actor[‘gender’]})

9 search = re.findall(‘birth_year=(\d{4})’, str(actor[‘page’])) 10 if len(search) &gt;= 1: 11 year_born = search[0] 12 else:

13 year_born = None

14 star.update({‘year_born’: year_born})

15 first_job = actor[‘page’].find(

16 ‘div’, 17 {‘class’:’filmo-category-section’}

18 ).find_all(

19 ‘div’, 20 {‘class’:[‘filmo-row even’, ‘filmo-row odd’]} 21 )[-1]

22 first_movie = re.findall(

23 ‘&lt;a href=”/title/.+”&gt;(.+)&lt;/a&gt;’,

24 str(first_job)

25 )[0]

26 star.update({‘first_movie’: first_movie})

27 first_movie_year = re.findall(

28 ‘.*(\d{4}).*’,

29 first_job.find_all(‘span’, {‘class’: ‘year_column’})[0].getText() 30 )[0]

31 star.update({‘year_first_movie’: first_movie_year})

32 credits = re.findall(‘(\d+)\scredits?’, str(actor[‘page’]))[0]

33 star.update({‘credits’: credits})

34 star_table.append(star)

35 return star_table

In [218]:

1 # RUN THIS CELL ONLY ONCE – IT WILL TAKE SOME TIME TO RUN

2 star_table = []

3 star_table = create_star_table(starlist)

100%|██████████| 100/100 [00:16&lt;00:00, 6.10it/s]

Your output should look like this:

[{‘name’: ‘Gal Gadot’, ‘gender’: 1,

‘year_born’: ‘1985’,

‘first_movie’: ‘Bubot’,

‘year_first_movie’: ‘2007’,

‘credits’: ’25’},

{‘name’: ‘Tom Hardy’, ‘gender’: 0,

‘year_born’: ‘1977’,

‘first_movie’: ‘Tommaso’,

‘year_first_movie’: ‘2001’,

‘credits’: ’55’}, …

1.5

1.6

name gender year_born first_movie year_first_movie credits

79 Joan Crawford 1 1906 Lady of the Night 1925 105

63 Daisy Ridley 1 1992 Only Yesterday 1991 32

72 Finn Jones 0 1988 Hollyoaks Later 2009 14

15 Jennifer Lawrence 1 1990 Monk 2006 30

35 Eiza González 1 1990 Lola: Érase una vez 2007 19

33 Dafne Keen 1 1966 The Refugees 2014-2015 4

43 Bill Paxton 0 1955 Crazy Mama 1975 94

61 Kaya Scodelario 1 1992 Moon 2009 23

12 Felicity Jones 1 1983 The Treasure Seekers 1998 42

58 Travis Fimmel 0 1979 I Used the Staff Solution 2001 26

In [244]:

Out[244]:

gender year_born credits

count 100.000000 100.000000 100.000000

mean 0.730000 1983.080000 38.470000

std 0.446196 12.664816 22.416379

min 0.000000 1906.000000 4.000000

25% 0.000000 1979.000000 22.000000

50% 1.000000 1985.500000 34.500000

75% 1.000000 1990.000000 51.000000

max 1.000000 2004.000000 122.000000

In [245]:

Out[245]:

name gender year_born first_movie year_first_movie credits

79 Joan Crawford 1 1906 Lady of the Night 1925 105

[246]:

Out[246]:

name object gender int64 year_born int64 first_movie object year_first_movie object credits int64 dtype: object

In [247]:

1 # Check the movies with ‘year_first_movie’ duplicated

2 df[df.year_first_movie.str.len() &gt; 4] Out[247]:

name gender year_born first_movie year_first_movie credits

3 Alexandra Daddario 1 1986 All My Children 2002-2003 51

23 Cara Delevingne 1 1992 Anna Karenina 2012/I 20

29 Robin Wright 1 1966 The Yellow Rose 1983-1984 54

33 Dafne Keen 1 1966 The Refugees 2014-2015 4

46 Jason Momoa 0 1979 Baywatch 1999-2001 27

60 Cole Sprouse 0 1992 Grace Under Fire 1993-1998 35

77 Rebecca Ferguson 1 1983 Nya tider 1999-2000 25

78 Julia Garner 1 1994 The Dreamer 2010/II 27

86 Auli’i Cravalho 1 2000 Moana 2016/I 4

96 Elodie Yung 1 1981 La vie devant nous 2002-2003 22

name gender year_born first_movie year_first_movie credits

93 Sophie Turner 1 1996 Another Me 2013 13

7 Dan Stevens 0 1982 Frankenstein 2004 37

59 Charlize Theron 1 1975 Children of the Corn III: Urban Harvest 1995 58

54 Katherine Waterston 1 1980 Americana 2004 43

21 Sophia Lillis 1 2002 The Lipstick Stain 2014 13

58 Travis Fimmel 0 1979 I Used the Staff Solution 2001 26

43 Bill Paxton 0 1955 Crazy Mama 1975 94

64 Emily Browning 1 1988 The Echo of Thunder 1998 30

22 Jessica Henwick 1 1992 St Trinian’s 2: The Legend of

Fritton’s Gold 2009 25

82 Bryce Dallas Howard 1 1981 Parenthood 1989 33

In [249]:

Out[249]:

name object gender int64 year_born int64 first_movie object year_first_movie int64 credits int64 dtype: object

name gender year_born first_movie year_first_movie credits age_at_first_movie

Laura

36 1 1985 My Family 2007 35 22

Haddock

How Did You

Connie Get In? We

85 1 1965 1984 51 19

Nielsen Didn’t See You

Leave

Children of the

Charlize

59 1 1975 Corn III: Urban 1995 58 20

Theron

Harvest

The New

Emma

13 1 1988 Partridge 2005 42 17

Stone

Family

PSI Factor:

Katheryn Chronicles of

41 1 1977 1999 61 22

Winnick the

Paranormal

Day of the

Christian

99 0 1966 Dead 2: 2005 13 39

Navarro

Contagium

Bill

4 0 1990 Järngänget 2000 30 10

Skarsgård

Nina

98 1 1989 Playing House 2006 41 17

Dobrev

Alison

28 1 1982 Stolen Poem 2004 61 22

Brie

Hugh Law of the

68 0 1968 1994 57 26

Jackman Land

1.7.1

In [259]:

1 # your code here

2 print(str(len(df[df.age_at_first_movie == 17].index))

3 + ‘ performers made their first movie at 17’)

8 performers made their first movie at 17

Your output should look like this:

8 performers made their first movie at 17

1.7.2

1.8

In [275]:

Out[275]:

name gender year_born first_movie year_first_movie credits age_at_first_movie

Sean Jane Austen in

42 1 1959 1980 122 21

Young Manhattan

The most prolific actress or actor in IMDb’s list of the Top 100 Stars for 2017 is Sean Young.

In [276]:

1 from IPython.core.display import HTML

2 def css_styling(): styles = open(“styles/cs109.css”, “r”).read(); return HTML(s 3 css_styling()

Out[276]:

# Web-Centric Computing Assignment 1 #
## Abstract ##

Epi de Dieu Ltée” is a noteworthy bakery and pastry shop in Quatres-Bornes. 
It has been set up in 2002 with the intent of providing the vicinity 
with baked goods and all things cake.
The owners thence set out to provide catering services and daily delivery of staple bakeries. 
Recent expansion brought such additions as assuring backup supply of goods to retail stores 
and home delivery of orders to the business’ services.
In the same vein, “Epi de Dieu Ltée” adopted a computerized business management solution, 
resulting in an extant, to-date IT set-up with a working internet connection; 
analogous to a client’s expected computing infrastructure.

---

## Introduction ##
### The Company ###

“Epi de Dieu ltée” is owned and run by its founder, Mrs Thomas,
who counts amongst the 4 employees of the business.
It comprises of a bakery contiguous to a retail outlet where its goods are sold
The bakery operates every day from 05:30 to 20:30, with the exception of 
Sundays on which it closes at 21:30.  
From its establishment,
it has succeeded to catch the interest of a regular loyal customer base with
its variety of baked & pastry products.  
Nonetheless, to continue being successful, EdD ltée must seek to modernise its 
operations to cope with the competition.


### Products & services ###

As part of its provided services, the bakery produces a certain daily supply of bread and 
cakes intended for individual consumption as well as for supplying local shops.
The shop also provides catering services for special occasions such as parties, 
weddings or anniversaries, 
and now also undertakes orders from large-scale retailers in the likes of 
the ‘Super-U’ and ‘Jumbo’ supermarkets.
Currently orders are placed either via phone call or in person on the premises.


An outline of some processes we are to consider yields:

- Taking orders
“Epi de Dieu ltée” offers customers the possibility of placing on order ahead of a 

- Responding to customer queries
“Epi de Dieu ltée” receives quite a number of phone enquiries 

+ Serving customers
To benefit from the advantages that this solution provides, “Epi de Dieu ltée” 
recently computerised their bookkeeping processes. Nonetheless, 
The person serving customers uses a spreadsheet to log sold items. The data is then 
input directly into their database tables

+ Delivery


### Problem Statement ###

The problems faced by the client can be outlined as:
- Info about the products of the shop are only accessible to people having access to the shop itself
> Which leads to:

- A large amount of redundant phone queries
	
- Taking orders exclusively via phone calls is inefficient in that it may lead to errors 

The fact that info about the products of the shop is only available to 
 


<!--- Edd ltd, hereinafter referred to as “the client”  is an ex

The problems faced by edd ltd are typical of 
With the advance of

-->

## Attempt at a solution ##

To the incurred problems, we propose a web-based solution: A website showcasing the client’s business
and services and acting as a portal to the later by enabling customers to place orders.
The aims of the website are various; to display updated information about the business and its products 
to customers, to provide customers a modern way of performing transactions as well as creating a 
web presence for the business in the view of identifying potential leads.


## Description of Proposed System ##

The proposed system is centered around a website.  
The latter would be host to information about the business, be a 
means of two-way communication with the business and enable users 
to buy products of the business.  
Users will have the option to register to benefit from a 
personalised experience.  
The solution will also feature a web-app that will only be 
accessible the business's owner.  
The web-app will be connected to the website's database and 
consist of a dashboard which will, for instance, display the 
description and of orders for the day and the business's stock.  
It will also double as a Point-Of-Sales app to be used at the shop's 
counter, replacing the current spreadsheet, such that sales 
immediately update stock in the database. ...  


## Justification ##

The client currently relies on traditional means of advertising 
such as business cards ...

A website enables the business to tap into a certain demographic 
unattainable before: 
that of the ever-growing user base of internet services.
We postulate that an online presence for Epi de Dieu ltée would 
help it gain an edge over its competitors in its field.  

Streamlined workflow with less interruptions.  
Increased productivity since employees aren’t required 
to answer phone calls etc.
A web-app has the advantage that it is easily scalable.  
It also, is consistently accessible from a range of devices 

An order portal produces direct revenue and measurable profit
 
 









## Technological considerations ##

The steps to build the solution are

Building a styling CSS framework to support the site’s 

Below is a rundown of the technologies to be 


#### HTML5 and CSS3 ####

The website's and web-app's front-end will be built using **HTML** as markup
language and **CSS** as style sheet language.  
It will be developped adhering the latest W3C specifications of the
HyperText Markup Language's and Cascading StyleSheets' syntax and semantics,
namely, **HTML5** and **CSS3**.

Constraints:
- Client-side: *Requires an HTML5 compliant user-agent*
- Server-side: *None*

#### CSS Preprocessing ####

A CSS preprocessor injects constructs from programming languages into CSS scripting.
It is a great consideration when seeking to build a CSS framework.
Preprocessing CSS *cascades* (pun intended) no dependencies down to the clien or server
infrastructure since it compiles to scripts in pure CSS3.

Constraints:
- Client-side: *None*
- Server-side: *None*

#### Linting ####

A linter is a tool developed to flag non-portable programming constructs 
or those which do not adhere to the language's semantics or philosophy, 
generally by means of static source code analysis.  
It is a tool which 
The linters we are to consider for our purposes are **CSSLint**, **JSLint**  

Constraints:
- Client-side: *None*
- Server-side: *None*

### AJAX ###

*Asynchronous JavaScript and XML* (**AJAX**) is a methodology employing user-generated events handling, 
data retrieval and DOM manipulation to 
Using raw AJAX calls creates no dependency (on javascript libraries for instance).

Constraints:
- Client-side: *A browser sporting a JavaScript engine*
- Server-side: *None*

### Markdown ###

**Markdown** is a mark-up language intended for web-writing.
It is intended to be as easy to write as it is easy to read.
As such, it would be a nice addition to the website's CMS to 
enable easy styling from the administrator.  
Markdown's syntax can easily be converted to HTML by parsing it on 
the server, thus adding no dependency of support by 
rendering engines.  

Constraints:
- Client-side: *None*
- Server-side: *None*


### PHP ###
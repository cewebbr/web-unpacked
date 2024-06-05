# Metadata about domains-annotated_v03.csv


## About the data

The table contains data about the top 116 websites in terms of monthly visits, according to SimilarWeb. These
websites are the ones whose domains are visible in SimilarWeb's free trial, without gaps in the names. They were 
consolidated from the ranks extracted from all industries. Each industry would display the top 75 domains.

The data was annotated on january 2024.


## Methodology

Information about the domains were checked mainly on Wikipedia (english). They were also accessed in incognito mode
to test for the need of login, if it charges users, an so on. In a few cases, some information was collected through 
other sources.

In some cases, the features were of a website were hard to underpin and were guessed based on Wikipedia information or 
a quick experience on the website. When the information was too unknown, it was left blank.


## Columns

### position

* The position in similar-web_full-rank_2023-ago-out.csv rank (for all industries).
* Originally extracted from the CSV file above.

### domain

* The domain according to similar-web_full-rank_2023-ago-out.csv. This might include 
  data regarding subdimains. In a few cases, the traffic to subdomains is the relevant one.
* Originally extracted from the CSV file above, and used to check for information.

### industry

* The topic of the domain, according to SimilarWeb classification.
* Originally extracted from the CSV file above.

### software_as_service

* Binary column that specifies if the website under the domain can be considered mainly 
  related to Software-as-a-Service (SaS). 
* Web search were not considered SaS.
* Examples: Office, Canva, OpenAI, Whatsapp.

### content_producer

* Binary column that specifies if there is content in the website under the domain that is
  produced by the website itself. 
* In case of markerplace or e-commerce, it specifies if there are products that are sold 
  by the website itself (e.g. Amazon products).
* Websites that are platforms, social networks, marketplace for third parties, are tipically 
  not considered content producers.
* News aggregators are not considered content producers as well, nor are web search engines.

### user_content_platform

* Binary column that specifies if the website under the domain works as a platform for content
  produced by users.
* Social networks are the main example of this. In marketplaces and e-commerce, platforms that 
  allow for third party sellers are considered user content platforms. 
* News aggregators are not considered user content platforms as the contributors are mostly 
  predefined by the website, and not voluntarely added.
* Comments made to a website, such as in some news websites, are not enough for them to be 
  considered user content platforms.
* Search engines are not considered user content platforms.

### needs_login

* Binary column that specifies if the website under the domain requires login to access the main content.
* News websites that block the access after a few pages are considered to require login.
* Messaging platforms tipically require logins
* E-commerce and marketplaces that allow for browsing without a login but require a login when making a 
  purchase are considered not to require a login. In some cases, like checking the cart for the selected 
  products, the need for a login was considered that the website requires login.
* Websites that require login for posting but not for reading were not considered to need login. Social 
  networks, for instance, are considered to need login because they tipically require it to read. 
  Exception, for example: reddit.

### charge_users

* Binary column that specifies if the website under the domain charges for the use of its main contents and 
  funcionalities.
* If the website charges for extra features that do not hinder the main use, we considered the website not 
  to charge its users
* In case of marketplaces, charges applied to sellers were not considered.

### mainly_web

* Binary column that specifies if the website under the domain refers to a business or activity that is 
  mainly contained in the Web. 
* Classical examples are: search engines, social networks, streaming.
* Classical counter examples are: websites for companies like coca-cola, samsung.
* News websites were considered mainly web.
* Marketplaces and e-commerce that are only intermediaries were considered mainly web, whereas those 
  that sell their own products were not.

### owner

* The final owner of the website, according to Wikipedia. 
* A website might be owned by a company, that might be owned by a holding, and so on. Whenever we could trace
  a parent company, we would follow it.
* In case of a company that is partially owned by others, we tipically considered the parent to own the 
  company if it controls at least 50% of the company.

### for_profit

* Whether the website is onwed by an organization that aims at profits.
* Typical exemples of non-profits are: those that declare themselves as non-profits and governments.

### owner_country

* Binary column that specifies the country associated to the final owner of the website.

### bought

* Whether or not the website (and business associated with it) was first created by a different owner than
  the current one.

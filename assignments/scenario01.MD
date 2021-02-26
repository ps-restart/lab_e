## Build A Publicly Accessible Website
______
Your task is to create a website that is accessible from the public internet.
### Part 1 -- Launch Your Website
____
<ol>1) Your Website must use a VM to run the web-server.</ol>
<ol>2) You can use any choice of web-server software (i.e Apache, NginX, etc.)</ol>

### Part 2 -- Make your Website Resilient
____
Your next task is to make your website resilient to potential outages. To do this, you must create a failover site in case the first site has a catastrophe. The failover site must be a second site that is physically distance from the first 2 )2 different data centers). A user must be able to use u single URL and have access to 2 different sites. you must be able to show one web server not available and your site still functions.

<ol>1. Add another web server in a physically distance data center.</ol>
<ol>2. Create a means to fail over to the other website in case of a failure.</ol>
<ol>3. You must be able to show that when one web server is unreachable, the other server is able to continue serving pages.</ol>

### Bonus: Putting it all together
<ol>1. Make your website capable of serving media objects.</ol>
<ol>2. Configure a way to synchronize the media content between the two web servers</ol>
<ol>3. Make sure the website can function even when a data center goes down.</ol>

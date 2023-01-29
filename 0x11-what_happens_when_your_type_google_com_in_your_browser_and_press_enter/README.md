# 0x11. What happens when you type google.com in your browser and press Enter

In this project, I am asked to write an article to explain all about the web 2.0 infrusture. Understanding this concept is very important for me as a fullstack software engineer.

## Task 0
<p>This question is a classic and still widely used interview question for many types of software engineering position. It is used to assess a candidate’s general knowledge of how the web stack works on top of the internet. One important guideline to begin answering this question is that you should ask your interviewer whether they would like you to focus in on one specific area of the workflow. For a front-end position they may want you to talk at length about how the DOM is rendering. For an SRE position they may want you to go into the load balancing mechanism.</p>

<p>This question is a good test of whether you understand DNS. Many software engineering candidates struggle with this concept, so if you do well on this question, you are already way ahead of the curve. If you take this project seriously and write an excellent article, it may be something that will grab the attention of future employers.</p>

<p>Write a blog post explaining what happens when you type https://www.google.com in your browser and press Enter.</p>

Requirements, your post must cover:

- DNS request
- TCP/IP
- Firewall
- HTTPS/SSL
- Load-balancer
- Web server
- Application server
- Database

I wrote [this](https://betascribbles.hashnode.dev/what-happens-when-you-type-googlecom-in-your-browser-and-press-enter) article.

## Task 2
<p>Add a schema to your blog post illustrating the flow of the request created when you type https://www.google.com in your browser and press Enter.</p>

The diagram should show:

- DNS resolution
- that the request hitting server IP on the appropriate port
- that the traffic is encrypted
- that the traffic goes through a firewall
- that the request is distributed via a load balancer
- that the web server answers the request by serving a web page
- that the application server generates the web page
- that the application server request data from the database

The image diagram I made is [here](https://github.com/betascribbles/alx-system_engineering-devops/blob/main/0x11-what_happens_when_your_type_google_com_in_your_browser_and_press_enter/1-what_happen_when_diagram.jpeg)

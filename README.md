# Heroku-Python


<img src="banner.png">

<hr>

<h3>  :computer: Environment and knowledge required. </h3>

<p>Hello, you may wondering why this repository is existing ?</p>

<p>Well, he completing my setup for practice web python (in this case for python), on this repository I'm gonna guide you to deploy an Heroku application who running with Python,Django,Postgre.</p>

<p>If you just want to deploy a python web service with django as client and server, take a look on my other repository : <a href="https://github.com/R3tr093/Python-DockerCompose">Python Docker-compose</a> you need docker-compose to run it, is just a quick setup for practice Django in a container, you have to find how to use Django for carrying web service by yourself.</p>

<p>You can use this application locally to practice and deploy it on heroku when you're ready to do it. So let me tell you about the few things you have to understand to follow the repository.</p>

<h4> :notebook: <i>the following things are required : </i> </h4>

<p><b>A free heroku account.</b></p>
<p><b><a href="https://devcenter.heroku.com/articles/heroku-cli" target="_blank">Heroku CLI</a></b></p>
<p><b>Python 3.7 localy</b></p>
<p><b>Postgres localy</b></p>
<p><b>Github localy</b></p>
<p><b>Basic knowledges of python  ( Not really necessary but it should help you ) </b></p>

<p>I write this by reading the <a href="https://devcenter.heroku.com/articles/getting-started-with-python" target="_blank">Heroku official documentation</a>, so if something seem don't work, take a look right there.</p>

<hr>

<h3> :open_file_folder: List of content </h3>

<ul>

<li><a href="#start">Prepare the app</a></li>
<li><a href="#deploy">Deploy the app</a></li>
<li><a href="#logs">View logs</a></li>
<li><a href="#scale">Scale the app</a></li>
<li><a href="">Declare app dependencies</a></li>
<li><a href="">Run the App locally</a></li>
<li><a href="">Push local changes</a></li>
<li><a href="">Provision add-ons</a></li>
<li><a href="">Start a console</a></li>
<li><a href="">Define config vars</a></li>
<li><a href="">Provisions a postgre Database</a></li>
</ul>


<h3 id="start">:construction_worker: Set up </h3>
<p>Download the heroku getting started repository by typing the command below : </p>
<code>git clone https://github.com/heroku/python-getting-started.git </code><br>
<p>Then move into the directory you just downloaded : </p>
<code>cd python-getting-started</code><br>

<p>Feel free to explore the content of the directory, it may be helpful </p>

<h3 id="deploy">:rocket: Deploy your application on heroku. </h3>
<code> heroku create </code><br><br>
<code> git push heroku master && heroku open </code><br>


<h3 id="logs">:lock_with_ink_pen: View logs</h3>

<code>heroku logs --tail</code><br>
<p><em><b>Then type ctrl + c if you want to quit the logs views.</b></em></p>


<h3 id="scale"> Scale the app </h3>

<p>Your app is running into a <b>dyno</b>, you can see dyno like a lightweight container, Free dynos will sleep after a half hour of inactivity (if they don’t receive any traffic). This causes a delay of a few seconds for the first request upon waking. </p>

<p>Also all of yours free dyno consume from a monthly quota of free dyno hours - as long as the quota is not exhausted, all free apps can continue to run.</p>

<p>checkout the status of dyno by the command below : </p>

<code> heroku ps </code><br>















# realtime-emotion-recognition-web-with-login-and-signup-authentication-using-python-flask

<h2>Modules Required</h2>
<p>We will implement login and registration functionality using the following modules.</p>
<ul>
<li><strong>Create and activate virtual environment</strong>: create a virtual environment by using the below command:</li>
<pre>
python -m virtualenv env
</pre>
<pre>
.\env\Scripts\activate.ps1
</pre>
<li><strong>Install required libraries</strong>: Install all the required libraries using the below command:</li>
<pre>
pip install -r requirements.txt
</pre>
</ul>
<h2>Create MySQL Database</h2>
<p>We need to create MySQL database and then <code>user</code> table to store user information. </p>
<p>We will create <code>user</code> table using below query.</p>
<pre>
CREATE TABLE `user` (
  `userid` int(11) NOT NULL,
  `name` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `password` varchar(255) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

ALTER TABLE `user`
  ADD PRIMARY KEY (`userid`);
</pre>

<h2>Run App</h2>
<p>Run the following command in terminal to open the flask app</p>
<pre>
python app.py
</pre>

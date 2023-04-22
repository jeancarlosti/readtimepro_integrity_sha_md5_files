# Ticapsoriginal making integrity LOG 
* Create log file with SHA and MD5 hash code for each file

## make python environment:
* Install pip first:
<pre><code>sudo apt-get install python3-pip
</code></pre>
* Then install virtualenv using pip3
<pre><code>sudo pip3 install virtualenv 
</code></pre>
* Now create a virtual environment
<pre><code>virtualenv venv
</code></pre>
* Active your virtual environment:
<pre><code>source venv/bin/activate
</code></pre>
* Enter on environment:
<pre><code>cd venv
</code></pre>

## Clone Ticapsoriginal_integrity_sha_md5_files repository:
<pre><code> git clone https://github.com/Tinoco/Ticapsoriginal_integrity_sha_md5_files.git
</code></pre>

## Make Integrity log:
<pre><code> python integrity.py
</code></pre>

![](https://ticapsoriginal.com/static/integrity.png)

* Any change on file change SHA hash code

[`100% pycodestyle coverage`](https://pypi.org/project/pycodestyle/)

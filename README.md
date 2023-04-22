# Ticapsoriginal making integrity LOG 
* Create log file with sha and md5 hash code for each file

## make python environment:
* install pip first:
<pre><code>sudo apt-get install python3-pip
</code></pre>
* then install virtualenv using pip3
<pre><code>sudo pip3 install virtualenv 
</code></pre>
* now create a virtual environment
<pre><code>virtualenv venv
</code></pre>
* active your virtual environment:
<pre><code>source venv/bin/activate
</code></pre>
* enter on environment:
<pre><code>cd venv
</code></pre>

## clone Ticapsoriginal_integrity_sha_md5_files repository:
<pre><code> git clone https://github.com/Tinoco/Ticapsoriginal_integrity_sha_md5_files.git
</code></pre>

## make Integrity log:
<pre><code> python integrity.py
</code></pre>

![](https://ticapsoriginal.com/static/integrity.png)

* any change on file change SHA hash code

[`100% pycodestyle coverage`](https://pypi.org/project/pycodestyle/)

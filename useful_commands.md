<h1>Git useful commands</h1>

$ git status <br>
$ git add . <br>
$ git clone <URL><br>
$ git diff --staged<br>
$ git commit -a (<i>skiping git add</i>)<br>
$ git rm --cached  (<i>rm from git</i>)<br>
$ git log:<br>
<p>	   -p  (<i>diff each commit</i>)</p>
<p>	   --word-diff (<i>only diffs</i>)<p>
	   --stat<br>
	   --pretty=oneline<br>
			    -graph<br>
	-<n> (<i>first n commits</i>)<br>
	--since=<n>.<some timelen><br>
	--until<br>
$ gitk (<i>GUI of diffs</i>)<br>
$ git remote:<br>
	     -v (<i>url, use in the cloned repo</i>)<br>
	     add <short name> <url><br>
//$ git fetch origin: fetches any new work that has been pushed to that server<br>
$ git pull <short name or URL><br>
$ git push <shortname> <branch>

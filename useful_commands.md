<h1>Git useful commands</h1>

	$ git status 
	$ git add . 
	$ git clone <URL>
	$ git diff --staged<
	$ git commit -a (<i>skiping git add</i>)
	$ git rm --cached  (<i>rm from git</i>)
	$ git log:<br>
		   -p  (<i>diff each commit</i>)
		   --word-diff (<i>only diffs</i>)
		   --stat
		   --pretty=oneline
				    -graph
		-<n> (<i>first n commits</i>)
		--since=<n>.<some timelen>
		--until
	$ gitk (<i>GUI of diffs</i>)
	$ git remote:
		     -v (<i>url, use in the cloned repo</i>)
		     add <short name> <url>
	//$ git fetch origin: fetches any new work that has been pushed to that server
	$ git pull <short name or URL><
	$ git push <shortname> <branch>

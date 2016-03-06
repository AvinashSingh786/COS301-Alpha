def:
	 xelatex -synctex=1 -interaction=nonstopmode *.tex
	

clean:
	rm -f *.aux *.synctex.gz *.toc *.log

upload:
	git init
	git add *
	git commit * -m "updated"
	git pull origin master
	git push origin master
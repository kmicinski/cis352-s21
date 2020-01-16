deploy:
	rm -rf docs
	jekyll build 
	rm -rf _site/docs
	cp -r _site docs
	git add docs
	git commit -m "webpage update"
	git push origin master

.PHONY: deploy


.PHONY: all
all:

include $(or \
	$(wildcard jekyll.make),\
	$(lastword \
		$(info Downloading jekyll.make...)\
		$(shell curl --progress-bar -Lo jekyll.make https://bit.ly/jekyll-make)\
		jekyll.make))


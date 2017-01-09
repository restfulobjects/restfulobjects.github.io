# restfulobjects.github.io

This site holds the Restful Objects Specification.


## Prep

The `master` branch has the generated site, while the `pages` site has the source.

The `pages` branch can be created in a worktree using:

	git worktree add -b pages ../restfulobjects.github.io-pages master


## Generating and Committing

In this `pages` worktree, use:

	bundle exec jekyll serve

This will recreate the site in the `_site` subdirectory, and allow the generated site to be viewed (at [http://localhost:4000](http://localhost:4000).


Once happy, copy over the `_site` subdirectory over the `master` worktree, eg:

	cd ../restfulobjects.github.io
	cp -R ../restfulobjects.github.io-pages/_site/* .




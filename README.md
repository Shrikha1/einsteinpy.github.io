<<<<<<< HEAD
Visit https://einsteinpy.org for details about the EinsteinPy Project!
=======
# EinsteinPy Main Site

This is the GitHub repository for the Bokeh Project Main Site, [einsteinpy.org](https://einsteinpy.org). The Main Site is a portal to guide users to other project resources and sites. The repository for the source code of Bokeh itself can be found at [github.com/einsteinpy/einsteinpy](https://github.com/einsteinpy/einsteinpy).

Full docs for setting up a GitHub Pages Jekyll blog [can be found here](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll).

# Building Locally

## Using Docker

After installing [`docker`](http://docker.com/), run `make serve` to build and run the website within the a container built from the [`jekyll/jekyll` image](https://hub.docker.com/r/jekyll/jekyll/) that contains all the necessary prerequisites. The site will be available at `http://localhost:4000`. Modifying source files will cause the website to rebuild in real time (refresh the browser page to see changes).

## Manually

To build manually, you will need to have Ruby>=2.1 installed on your system. If necessary, run 

    gem install bundler
    
The first time you build locally you will need to install necessary dependcies. In the top level direcotory of this repository, run:

    bundle install
    
Then, to serve the site, run:

    bundle exec jekyll serve
    
The site will be available at `http://localhost:4000`. While this program remains running, you can edit the source files and Jekyll will automatically rebuild the site (refresh the browser page to see changes).
>>>>>>> 3eeea6d... First Push

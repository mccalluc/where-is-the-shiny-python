Looking for:
- Python backend
- Web frontend
- Dashboard UI: No code needed in frontend
- Dashboard UI: Multiple linked visualizations
- Extensible
- Performant with large datasets
- Open source

# Threads

(Links from these have been followed below.)
- ["I wish there was some abstraction to generate a Dash like output from Jupyter"](https://news.ycombinator.com/item?id=16961511): April, 2018
- ["notes from our discussion on dashboarding at the ipywidgets workshop"](https://github.com/jupyter-widgets/ipywidgets/issues/2018): March 24, 2018
- ["how dashboarding could be accomplished in JupyterLab"](https://github.com/jupyterlab/jupyterlab/issues/1640): Feb 7, 2017

# Tools

## Plotly Dash
- [home](https://dash.plot.ly/)
- [github](https://github.com/plotly/dash)

## pyviz/Panel
- [home](https://panel.pyviz.org/)
- [github](https://github.com/pyviz/panel) (150 stars, 15 forks, 10 contributors, last commit Apr 14, 2019)

> Panel is novel in that it supports nearly all plotting libraries, works just as well in a Jupyter notebook as on a standalone secure web server, uses the same code for both those cases, supports both Python-backed and static HTML/JavaScript exported applications

## pyviz
- [home](https://pyviz.org/)

> PyViz is a coordinated effort to make data visualization in Python easier to use, easier to learn, and more powerful. 

## Bowtie
- [readthedocs](https://bowtie-py.readthedocs.io/en/latest/)
- [github](https://github.com/jwkvam/bowtie) (645 stars, 54 forks, 3 contributors, last commit Feb 10, 2019)
- [gallery](https://github.com/jwkvam/bowtie/wiki/Gallery)

## Jupyter Dashboards (*inactive*)
- [readthedocs](https://jupyter-dashboards-layout.readthedocs.io/en/latest/)
- [github](https://github.com/jupyter/dashboards) (900 stars, 174 forks, 17 contributors, last commit Aug 30, 2018)

Jupyter extension. Cells can be arranged in grids, rather than occupying the full width. Project had initial funding from IBM, then lost energy.
> Easy drag-and-drop layout of cell outputs in a grid, one-click publish, secure execution of the notebook by not accepting code execution from the browser.

## Jupyter appmode
- [github](https://github.com/oschuett/appmode) (205 stars, 35 forks, 5 contributors, last commit Mar 13, 2019)

Jupyter extension
> When a notebook is opened in appmode, all code cells are automatically executed. In order to present a clean UI, all code cells are hidden and the markdown cells are read-only."

## Voila
- [github](https://github.com/quantstack/voila) (169 stars, 23 forks, 5 contributors, last commit Apr 5, 2019)
- [binder demo](https://mybinder.org/v2/gh/QuantStack/voila/stable?urlpath=voila/tree/notebooks)

Alternate notebook server
> - By default, voila disallows execute requests from the front-end, disabling the ability to execute arbitrary code.
> - By defaults, voila runs with the strip_source option, which strips out the input cells from the rendered notebook.

## ThebeLab
- [readthedocs](https://thebelab.readthedocs.io/)
- [github](https://github.com/minrk/thebelab) (77 stars, 18 forks, 11 contributors, last commit Mar 8, 2019)

Javascript library: Code snippets in HTML are sent to JupyterLab for eval, and the results are shown. Not sure if communication between separate components in HTML is possible.

## jupyterlab-dash
- [github](https://github.com/plotly/jupyterlab-dash) (121 stars, 16 forks, 4 contributors, last commit Mar 24, 2019)
> A JupyterLab extension for rendering Plotly Dash apps as a separate window

# Comparisons

## [Bokeh vs. Dash](https://blog.sicara.com/bokeh-dash-best-dashboard-framework-python-shiny-alternative-c5b576375f7f): January 30, 2018
> I would use Dash by default:
> - it uses plotly for python which makes it very powerful
> - it uses React on the frontend which makes it easy add components
> - I coded more easily on Dash than on Bokeh, which confirms the opinion of other users I cited
>
> If you’re still unsure about which one to choose:
> - Do a POC on Dash of your most critical features
> - Do a POC on Bokeh if you got blocked by a lack of interactions between graphs (like panning multiple graphs at the same time)
> - Then decide if you want to sacrifice some features to use Dash or if you’re fine with Bokeh

## [Shiny vs. Dash](https://www.rkingdc.com/blog/2019/3/6/shiny-vs-dash-a-side-by-side-comparison): March 6, 2019
> Shiny is a sleek, feature rich framework. It lowers the barrier to entry for creating rich interactive web apps but is also hackable, for those who want to build something complex and customized and who have the will to hammer though. The Shiny community is awesome.
>
> Dash is pretty new and still a little rough around the edges. It was built to be customized, so those who love hacking and tweaking may find a friend in Dash. And since it is built on Python and Flask, the ecosystem available for use in Dash apps is already huge. 

# Useful Resources
This repository gathers useful resources on some economics, research, programming, GIS, and other miscellaneous topics. Its motivation began after realizing that I had seen so many interesting references in the last year, but failed to save them. This aims to be a tracker of stuff I find useful and hopefully help others in their work.<br>
This repository was inspired by many others, like the ones done by [João Pedro Vieira](https://github.com/jpgmv1998/random_references?tab=readme-ov-file#writing-tips), [Ricardo Dahis](https://github.com/rdahis/paper_template), etc.<br>
Lastly, comments and suggestions are welcome! You can reach me on my [e-mail](mailto:vinicius.hector@outlook.com) or my [Twitter](https://x.com/hec_vini).
### Repository Rules
Items here must follow a description rule:<br>
- [Resource name, Author](link): describe it briefly (no more than two sentences). Focus on why it is useful.<br>

Also, keep it simple. Do not fill it with multiple items on the same topic.

### Outline
Content here is organized by topics:<br>

1. Econometrics
2. R
3. Python and GIS
4. Research in Economics
5. Miscellaneous
6. Environment

---

### 1. Econometrics
- [DiD Handbook](https://github.com/IanHo2019/DID_Handbook): a repository with some Diff-in-Diff methods and when to use each.

### 2. R
- [Awesome Packages](https://github.com/HecVini/AwesomePackages): my own list of R packages to use. Categorized into four sections: exploratory data analysis (EDA), data visualization, econometrics, and APIs.

### 3. Python and GIS
- [Pyarrow and Pyogrio](https://gis.stackexchange.com/questions/469503/speed-up-reading-gpkg-as-geopandas-dataframe): a much faster way to load .gpkg and .shp files in Python. Believe me, this will save you a lot of time.
- [Google Earth Engine API](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api): run GEE queries in Pyhton. If you are a VSCode user, check also [this](https://stackoverflow.com/questions/78374548/no-authentication-box-appears-when-authenticating-google-earth-engine-gee-pyth). Also, recall to properly set your Google Drive folder. More info [here](https://stackoverflow.com/questions/71917970/how-to-export-google-earth-engine-images-to-local-files-using-python).
- [Parallel Processing](https://www.packetswitch.co.uk/what-is-concurrent-futures-and-how-can-it-boost-your-python-performance/): use all of your GPUs to run code (especially loops). I wish I had known this years ago. This saves A LOT of time.
- [tqdm library](https://github.com/tqdm/tqdm): a progress bar with ETA. Useful for big loops.
- [gc (Garbage Collection)](https://stackify.com/python-garbage-collection/): clean cache to avoid RAM overload. Make sure to collect your gargabe when running heavy loops.

### 4. Research in Economics
- [Tips for Presentations in Applied Micro Talks, by Jesse Shapiro (Harvard University)](https://scholar.harvard.edu/files/shapiro/files/applied_micro_slides.pdf): straightforward tips on it. It has concrete examples of what to do (and what not to do), with some humor.
- [Tips on Writing Papers in Economics, by Plamen Nikolov (IZA)](https://docs.iza.org/dp15057.pdf): complete guide with concrete examples on it. It has suggestions for every part of a paper.
- [Writing Papers: A Checklist, by Michael Kremer (University of Chicago)](http://qed.econ.queensu.ca/pub/faculty/sumon/mkremer_checklist_paper.pdf): a concise checklist of what a paper must have.
- [Paper Template](https://www.overleaf.com/latex/templates/basic-working-paper-template-economics-and-management/bwpmkcbynmzj): overleaf TEX template for papers in economics.

### 5. Miscellaneous
- [GitHub Copilot (free for students)](https://dev.to/twizelissa/how-to-enable-github-copilot-for-free-as-student-4kal): imagine having a ChatGPT in your IDE? If you are a student, you can have it for free on VSCode.

### 6. Environment
- [ctrees.org](https://ctrees.org/products/land-carbon): startup that estimates above ground carbon for all forests in the world.
- [CHIRPS](https://www.chc.ucsb.edu/data/chirps): daily precipitation estiamtes for the whole world since the 80s. It uses stationary satelites to do it. 
- [FIRMS](https://firms.modaps.eosdis.nasa.gov/map/): fire data for the whole world (discover the details).
- [SRTM](https://www.earthdata.nasa.gov/sensors/srtm#:~:text=The%20Shuttle%20Radar%20Topography%20Mission,global%20dataset%20of%20land%20elevations.): topological rasters for the whole world. Just insert the desired bbox and download the correspondent .tiff file. 
- [Carbon Rating Agencies](https://www.sylvera.com/blog/what-is-a-carbon-credit-agency): companies that evaluate the quality of carbon removal/reduction projects globally.
- [Berkeley Carbon Trading Project](https://gspp.berkeley.edu/research-and-impact/centers/cepp/projects/berkeley-carbon-trading-project): all carbon offests issued by Verra, Gold Standard and ACR with its metadata. Lead by Prof. Barbara Haya.

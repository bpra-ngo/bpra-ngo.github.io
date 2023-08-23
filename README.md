# bpra-news-static
BPRA's static news website. Static wordpress files generated by Simply Static.
This repository is hosted on github pages and the website link is https://bpra-ngo.github.io

## How to update
The workflow currently is <br>
```develop wordpress locally -> generate a static version of the website -> host on github pages```

To update the website visible on bpra-ngo.github.io, you must:
1. Clone this repo.
2. Develop Locally (See https://github.com/bpra-ngo/bpra-news-website)
3. From WP's dashboard, find Simply Static
4. Go to the Deployment tab and set Deployment Settings > Deployment Method > Local Directory
5. Under Local Directory set PATH to point to this repository on your local machine

After that, every time you make a change to the website, generate a new static version from the plugin and commit and push the files to the remote repo.

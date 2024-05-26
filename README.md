# Scumbag Dive Bar Tour

Exploring the scummiest, divey-est bars in Lakewood, OH. View the live site at [https://derekpcollins.github.io/scumbag-dive-bar-tour/](https://derekpcollins.github.io/scumbag-dive-bar-tour/).


## 💻 Local Setup

### Clone the repo
Clone this repository to your local machine (it will install to whatever directory you're currently in):

```
cd directory-to-install-to
git clone git@github.com/derekpcollins/scumbag-dive-bar-tour.git
```

The above assumes SSH, but you may prefer to use HTTPS – [check the repo](https://github.com/derekpcollins/scumbag-dive-bar-tour) for alternative methods.


### Run the site locally

```
npx serve
```

Visit [http://localhost:3000/](http://localhost:3000/) in your browser (or whichever port its running on).

## ✍️ Contributing

Make sure your local repo is up-to-date:

```
git pull
```

It's best practice to work within your own branch:

```
git checkout -b your-new-branch
```

Make your edits, add any new files and commit your changes:

```
git add --all
git commit -am "Description of your changes here"
```

Push your local branch to the remote repo:

```
git push origin your-new-branch
```

When you're ready to merge your changes into `main`:

```
git checkout main
git pull origin main
git merge your-new-branch
git commit -am "Mergeing your-new-branch into main"
git push origin main
```
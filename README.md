# GAM Coach

An interactive tool to help everyday users discover actionable strategies to obtain desired AI decisions.

[![build](https://github.com/anonchi/gam-coach/workflows/build/badge.svg)](https://github.com/anonchi/gam-coach/actions)
[![license](https://img.shields.io/pypi/l/gamcoach?color=blue)](https://github.com/anonchi/gam-coach/blob/master/LICENSE)

|<img src='https://i.imgur.com/yOmEBz6.png'>|
|:---:|
|<a href="https://youtu.be/Z2vdqZFKNeg"> 📺 Demo Video for "GAM Coach: Towards Interactive and User-centered Algorithmic Recourse"</a>|

## Live Demo

For a live demo, visit: <https://anonchi.github.io/gam-coach/>

## Running Locally

Clone or download this repository:

```bash
git clone git@github.com:anonchi/gam-coach.git

# use degit if you don't want to download commit histories
degit anonchi/gam-coach.git
```

Install the dependencies:

```bash
cd gamcoach-ui
npm install
```

Then run GAM Coach:

```bash
npm run dev
```

Navigate to [localhost:5005](https://localhost:5005). You should see GAM Coach running in your browser :)

## Use the Python Library

You can also use GAM Coach as a Python library to generate customizable counterfactual examples for generalized additive models (GAMs). For details, read the [documentation](https://anonchi.github.io/gam-coach/docs/gamcoach).

```bash
pip install -e .
```

## Set Up Your Own GAM Coach

In the [demo page](https://anonchi.github.io/gam-coach), we provide five demos with the most commonly used datasets in the algorithmic recourse literature. You can easily set up a GAM Coach for your own GAM model (with only one function call). See the [documentation](https://anonchi.github.io/gam-coach/docs/gamcoach/gamcoach.html#get_model_data) for details.

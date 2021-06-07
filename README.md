# WikiPathways Curation Template

Template repository to set up pathway curation for the subset of WikiPathways, as
specified in the `pathways.txt` file.

## Step 0. Requirements

You need the following programs and experience with a `Makefile`:

* curl
* git
* zip
* java
* javac
* bash

## Step 1: Update the GPML files

First, make sure the `pathways.txt` files is updated to list the pathways you want
to curate.

Then, do:

```
make fetch
```

## Step 3: Create the RDF (Turtle)

```
make
```

Make sure that the GPML and the `.rev` files are under version control to track
the history of the pathway.

### Step 4: Run the validation tests

```
make check
```

### Step 5: (optional) Publish everything online

For this, enable GitHub Pages and add the files in `reports/` to the revision
control, including the `index.md` in the root folder.

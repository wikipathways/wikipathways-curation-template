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


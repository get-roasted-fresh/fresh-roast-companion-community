# Curated community recipes

Add **one JSON file per recipe** exported from Coffee Roast Tracker (or compatible).

## Naming

Use a **stable, versioned** basename so links do not break when you revise a curve:

- Good: `sr540-medium-city-120g-v1.json`, `sr540-medium-city-120g-v2.json`
- Avoid: `my-recipe.json` being overwritten in place after people have already downloaded it

## Pull request checklist

- File validates as JSON.
- Recipe opens in the app via **Import recipe (.json)** without errors.
- You have added a matching row to **`community-recipes-index.json`** (see **CONTRIBUTING.md**).
- PR states **license** and **attribution** (see **RECIPE_LICENSE.md**).

When this folder is empty, the manifest’s `recipes` array may be `[]` until the first accepted contribution.

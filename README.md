# Which frozen dessert products should be blocked from launch because of Product Data quality issues?

A Product Data quality audit for a frozen dessert manufacturer, inspired by real Product Information Management (PIM), ERP, and food labeling workflows used in the food industry.

## The business question

A frozen dessert manufacturer is preparing **90 products** for commercialization, but not every product contains complete and compliant Product Data.

**Which products should be blocked from launch because mandatory labeling information is missing or inconsistent?**

## The answer

I audited **90 frozen dessert products** across six frozen dessert categories using Product Data validation rules based on food labeling and PIM workflows.

### Executive summary

- **90 products reviewed**
- **48 approved for launch**
- **18 approved with warnings**
- **24 blocked from launch**

The blocked products contained critical issues such as missing allergens, incomplete Nutrition Facts, incorrect ingredient declarations, or missing mandatory product attributes.

## How I got there

Each product was validated against mandatory Product Data fields before publication in a PIM environment.

Validation included:

- Ingredient declaration.
- Allergen declaration.
- Nutrition Facts completeness.
- Product attributes (net weight, storage temperature, shelf life, serving size).
- Packaging and commercialization information.

## Product categories audited

| Category | Products |
|----------|----------|
| Ice Cream Tubs | 28 |
| Ice Cream Bars | 18 |
| Frozen Cheesecakes | 12 |
| Frozen Cakes & Tortes | 14 |
| Frozen Mousses & Desserts | 10 |
| Frozen Dessert Cups | 8 |

**Total:** 90 products.

## Validation rules

Products were blocked whenever one or more mandatory fields failed validation.

| Validation Rule | Severity |
|-----------------|----------|
| Missing allergen declaration | Block |
| Missing Nutrition Facts | Block |
| Missing ingredient list | Block |
| Net weight missing | Block |
| Storage temperature missing | Warning |
| Shelf life missing | Warning |
| Serving size inconsistent | Warning |
| Product description incomplete | Warning |

## Business impact

A launch with incomplete Product Data can create regulatory compliance risks, incorrect consumer information, and operational issues across ERP, PIM, and retail channels.

## What I'd do next

1. Complete missing mandatory attributes.
2. Validate Nutrition Facts against approved formulations.
3. Resolve ingredient and allergen inconsistencies.
4. Revalidate blocked SKUs before publication.

## Tools used

- FoodChecker (PIM system)
- 3LM (ERP + POS)
- Microsoft Excel
- Google Looker Studio
- GitHub Markdown

## Caveats

This repository uses a **synthetic dataset** created exclusively for portfolio purposes, inspired by real food labeling and Product Data validation workflows.

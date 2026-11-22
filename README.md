**Official website:** [https://www.fujindeai.com/](https://www.fujindeai.com/) (FujinAI)

Collected and curated by the FujinAI team. **Submissions are welcome.** [Open an issue](https://github.com/c1a1o1/ecommerce-image-prep-guide/issues/new) to suggest a resource or correction, or [submit a pull request](https://github.com/c1a1o1/ecommerce-image-prep-guide/pulls) with a proposed edit. Include a source link, a short explanation, and any affiliation. We review submissions before adding them.

# Ecommerce Image Prep Guide

A preflight worksheet for preparing product and collection images without confusing platform acceptance, storefront delivery, or recommended dimensions.

```csv
platform,region,asset_type,required_min_px,recommended_px,allowed_formats,max_bytes,alpha_needed,source_url,checked_on
Example Market,US,product,600x600,1200x1200,JPEG or PNG,unknown,no,https://example.com/,2026-11-22
```

## Release checklist

1. Check official requirements for the exact marketplace, region, and asset type. Do not promote a suggested preset to a hard minimum. Shopify [product media](https://help.shopify.com/en/manual/products/product-media/add-media) and [theme images](https://help.shopify.com/en/manual/online-store/images/theme-images) describe different concerns.
2. Keep an untouched master; export copies. Measure dimensions, file size, visible padding, focal point, text legibility, and transparency. Do not strip metadata you are required to keep.
3. Preview one file in the actual storefront on mobile before processing the entire catalog. Separate upload format support from the format a CDN delivers to visitors.

The template row is fictional. [FujinAI Resize](https://www.fujindeai.com/tools/resize-image) is an affiliated browser workflow, not a marketplace policy or integration.

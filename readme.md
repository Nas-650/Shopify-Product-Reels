# Shopify Reels Experience Template

Elevate your Shopify storefront with an engaging **Reels-Style Product Showcase**. This template introduces a vertical video-scrolling feature, inspired by social platforms like Instagram Reels, designed to captivate visitors and drive product interaction through immersive video content.

## What’s Included

- **Vertical Video Feed**: Seamless vertical scrolling through product-focused videos, echoing the mobile-native reel format.
- **Clickable Product Modules**: Each video links directly to its associated product page for smooth navigation and high conversion potential.
- **Slick Slider Integration**: Powered by the vertical mode of the [Slick Slider](https://kenwheeler.github.io/slick/), providing an intuitive and touch-friendly user experience.
- **Easily Adjustable**: Fully customizable components — structure, styling, and metafield labels — to fit any store’s needs.

## File Breakdown

- `reels-product.liquid` – Core layout file for the reels experience.
- `reels.css` – Starter stylesheet for visual customization.
- `product-video-card` – Component logic for displaying and linking each product’s video content.

## Requirements

- **Slick Slider Library**: Make sure to include Slick Slider’s JS and CSS in your theme for full functionality.
- **Product Metafield Setup**: A metafield (default: `reel`) should be defined in your product settings, pointing to the video content. You can rename this in the code if you prefer a different metafield key.

## How to Use

1. **Add Template Files**: Place the `reels-product.liquid` file into your theme’s template directory, and upload `reels.css` to your theme’s asset folder.
2. **Define Video Metafields**: In your Shopify admin, set up a metafield for each product containing the video URL or file (using the name `reel`, unless you modify it).
3. **Connect Videos**: Ensure products selected for the reel display have valid video entries.
4. **Style to Match Your Brand**: Customize the `reels.css` file for alignment with your store’s look and feel.

## Personalization Tips

- **Change the Metafield Key**: If your store uses a different metafield naming convention, adjust the references in `reels-product.liquid`.
- **Tailor the Design**: Tweak `reels.css` to fine-tune spacing, transitions, colors, and responsiveness.

## Get Involved

Suggestions, improvements, or contributions? Open a pull request or issue to help evolve this tool.

## Licensing

Distributed under the MIT License — free to use and adapt with proper attribution.
# gyeb-assets

Public image hosting for marketing assets. Photos only, nothing sensitive.

## Purpose

This repo stores images so they can be served over public raw URLs and re-hosted by third-party platforms such as Shopify, Klaviyo, and Buffer.

## How it works

An image is pushed to this repo, GitHub serves it at a public raw URL immediately, and that URL is pasted into Shopify / Klaviyo / Buffer which then rehost the image themselves. This avoids the download, upload, copy-CDN-URL, paste loop.

## Raw URL pattern

    https://raw.githubusercontent.com/growyouredgesback/gyeb-assets/main/PATH-TO-FILE
    

---
language:
- en
- multilingual
license: mit
tags:
- bluesky
- social-media
- posts
dataset_info:
  features:
    - name: text
      dtype: string
    - name: created_at
      dtype: string
    - name: author
      dtype: string
    - name: uri
      dtype: string
    - name: has_images
      dtype: bool
    - name: reply_to
      dtype: string
  config_name: default
  splits:
    - name: train
      num_examples: 7877660
---

![Bluesky Posts Dataset Overview](bskyposts.png)

# 8 Million Bluesky Social Posts Collection

I've collected and curated 8 million public posts from Bluesky Social between November 27 - December 1, 2024, with an additional 12 million posts coming in the upcoming weeks. This growing dataset aims to provide researchers and developers with a comprehensive sample of real world social media data for analysis and experimentation. This collection represents one of the largest publicly available Bluesky datasets, offering unique insights into social media interactions and content patterns.

## Dataset Overview

### Key Information
- **Source**: Bluesky Social Platform
- **Time Range**: Nov 27 - Dec 1, 2024
- **Format**: JSONL
- **Curator**: Alim Maasoglu
- **Primary Language**: English (includes other languages)

### Data Structure
Each post entry contains:
- `uri`: Unique post identifier
- `created_at`: Post creation timestamp
- `text`: Post content
- `author`: Author information
- Additional metadata (images, replies, etc.)

### Potential Applications
- Social media content analysis
- Language processing research
- Trend analysis
- Content recommendation systems
- Social network analysis

### File Organization
- Files are chronologically organized
- Each file is approximately 140MB
- Naming format: `posts_[DATE]_[TIME].jsonl`

## Usage Notes
This dataset is intended for research and development purposes. Users should comply with Bluesky's terms of service when utilizing this data.

## Acknowledgments
Data collected from Bluesky Social's public posts. Special thanks to the Bluesky community.

## License
This dataset is released under the MIT License.
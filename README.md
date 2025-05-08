# YouTube Trending Videos Analysis

This project analyzes YouTube trending video data to uncover patterns in trending duration, engagement metrics, and tag usage. The analysis is performed using Python in a Jupyter Notebook (`yt trend.ipynb`) and focuses on visualizations to explore relationships between trending duration and various video attributes.

## Dataset

The dataset (`USvideos_modified.csv`) contains information about YouTube videos that trended in the United States, including:
- Video metadata (e.g., `video_id`, `title`, `channel_title`, `category_id`)
- Engagement metrics (e.g., `views`, `likes`, `dislikes`, `comment_count`)
- Trending metrics (e.g., `trend_day_count`, `trend.publish.diff`, `last_trending_date`)
- Tag-related metrics (e.g., `tags_count`, `trend_tag_total`, `tag_appeared_in_title`)

**Note**: The `category_id` column in the provided dataset is not descriptive (all values are "category_id"). The analysis uses `channel_title` as a proxy for category analysis.

## Requirements

To run the notebook, install the required Python packages:

```bash
pip install numpy pandas matplotlib seaborn nltk

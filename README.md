# Player-classification-using-unsupervised-machine-learning

Clustering is a core technique in marketing analytics — used to segment customers, identify behavioral groups, and target strategies effectively. The same logic applies to football: instead of treating players only by predefined positions, clustering helps uncover underlying roles and patterns that better explain performance.

This project applies that idea to Fantasy Premier League (FPL) data. Data Source: https://github.com/vaastav/Fantasy-Premier-League/

**K-Means** → shows how new clusters can reveal player roles that make more sense than traditional positions.

**Gaussian Mixture Models (GMM)** → highlights K-Means shortcomings and improves by allowing soft memberships (players can belong to multiple roles with probabilities).

## What’s inside
player_classification.ipynb → notebook with data prep, clustering, and visualizations.
Visual comparisons of position-based vs cluster-based grouping.
Cluster evaluation against real established profiles

## Why this matters
Players don’t always fit cleanly into positions. Clustering offers a better way to segment roles, capture overlaps, and explain performance patterns.

## Future work
- Add more characteristics features to better define roles
- Implement GMM recommendations for tactical player selection

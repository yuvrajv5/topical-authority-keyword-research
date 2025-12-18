# Topical Authority Keyword Research

An AI-powered SEO agent that generates comprehensive topical authority maps with interactive visualizations.

## Features

- **Automated Topic Discovery**: Executes 15+ web searches to discover the topic landscape
- **Keyword Extraction**: Extracts primary keywords, long-tail variations, and PAA questions
- **Intelligent Clustering**: Organizes keywords into Pillar → Cluster → Supporting hierarchy
- **Competitive Analysis**: Analyzes top competitors with strengths/weaknesses
- **Priority Scoring**: Scores keywords based on intent, competition, gaps, value, and effort
- **Interactive HTML Reports**: Generates beautiful reports with D3.js force-directed graphs

## Output Example

The agent generates interactive HTML reports with:

- **Topic Cluster Visualization**: Draggable D3.js graph showing topic relationships
  - Blue nodes = Pillar content (write first)
  - Green nodes = Cluster content (write second)
  - Orange nodes = Supporting content (write last)
- **Content Creation Order**: Numbered table showing exact order to write content
- **Keyword Database**: Sortable/filterable table with all keywords
- **Competitive Landscape**: Competitor cards with content gap analysis
- **Content Roadmap**: Phased approach (Foundation → Clusters → Long-tail)
- **Internal Linking Strategy**: Hub-and-spoke diagram with linking rules

## Files

```
.claude/agents/
└── welco-topical-authority.md    # The agent instructions

projects/topical-authority/
├── virtual-receptionist-topical-map.html    # Example output
├── virtual-receptionist-topical-map.md      # Markdown version
└── servicenow-development-topical-map.html  # Example output
```

## Usage

1. Copy the agent file to your `.claude/agents/` directory
2. Run the agent with a topic: "Create a topical authority map for [YOUR TOPIC]"
3. The agent will:
   - Execute web searches
   - Extract and cluster keywords
   - Analyze competitors
   - Generate an interactive HTML report

## Example Topics Generated

- **Virtual Receptionist** - 85+ keywords, 5 pillars, 14 clusters
- **ServiceNow Development** - 90+ keywords, 6 pillars, 16 clusters

## Requirements

- Claude Code CLI or similar AI coding assistant
- Web search capability
- File write access

## License

MIT License

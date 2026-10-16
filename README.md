# FanOut Query Simulation

A browser based tool for exploring query fan out concepts in AI powered search and Generative Engine Optimisation (GEO).

FanOut Query Simulation lets users enter a core topic, define searcher personas, and explore simulated conversational prompts and related search queries. It provides a visual query tree and downloadable CSV and Excel reports.

## Features

- **Topic analysis:** Enter a product, service, technology or subject to explore.
- **Searcher personas:** Define up to five user archetypes with different search intents.
- **AI engine selection:** Select ChatGPT and Gemini in the simulation interface.
- **Simulated query expansion:** Generate conversational prompts and associated query branches.
- **Visual query tree:** Explore the relationship between the topic, personas and generated queries.
- **Detailed query log:** Review personas, conversational prompts, fan out queries and assigned engines.
- **CSV export:** Download simulation results as a CSV file.
- **Excel export:** Export results to an XLSX spreadsheet.
- **AlsoAsked integration option:** Includes an interface option for enriching simulated branches with question research.
- **Dark interface:** A modern interface designed for query exploration and analysis.

- Demo- https://selvaarchunan.github.io/fanout-query-simulation/

## Getting Started

### Requirements

- A modern web browser.
- An internet connection to load the external libraries and fonts used by the application.
- Optional API credentials for future or extended integrations.

### Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Enter a core topic or entity.
4. Add up to five searcher personas.
5. Configure the available simulation options.
6. Run the simulation.
7. Review the query tree and detailed results.
8. Export the results to CSV or Excel.

## Technology Stack

- HTML5
- CSS3
- JavaScript
- SheetJS for Excel exports
- Google Fonts
- Browser based interface and visualisation

## How It Works

The current implementation uses predefined query templates to simulate search intent expansion.

For each persona, it generates three types of conversational prompts:

1. Buying considerations
2. Alternatives and comparisons
3. Common problems and complaints

Each prompt is paired with a related query branch. The application displays these branches in a visual tree and a structured results table.

**Important:** The current version generates simulated query branches using predefined templates. It does not inspect the private internal search processes of ChatGPT or Gemini, and selecting an engine does not establish that a live query was sent to that provider.

## API Integrations

The interface contains optional fields for OpenAI, Gemini and AlsoAsked API keys.

In the current implementation, these keys are not connected to live API calls. The query generation workflow uses local predefined templates. The AlsoAsked enrichment option is also a user interface setting rather than an implemented live integration.

Do not enter production API keys into this version expecting them to be used for live queries.

## Use Cases

- Explore search intent for SEO research.
- Develop initial query ideas for GEO and AI search optimisation.
- Map different customer personas to conversational prompts.
- Build a starting list of questions for content planning.
- Export simulated query ideas for further analysis.

## Privacy

The current query simulation runs in the browser. It does not send the topic or persona data to an AI provider through a live API integration.

The page loads external resources, including fonts and the SheetJS library, from third party services. Avoid entering confidential business information when using externally hosted resources.

## Limitations

- Query branches are generated from predefined templates.
- Live OpenAI, Gemini and AlsoAsked integrations are not implemented.
- The generated queries should be treated as research ideas, not verified search data.
- Results do not represent confirmed internal AI search activity or actual search volume.
- The interface is a prototype and may need additional testing before production deployment.

## Deployment

You can host this static application with GitHub Pages.

For a root level landing page, save the HTML file as `index.html`, push it to the repository and enable GitHub Pages in the repository settings.

## Contributing

Contributions, feature suggestions and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make and test your changes.
4. Submit a pull request.

## Licence

Add a `LICENSE` file before publishing the project for reuse. The MIT Licence is an option if you intend to permit broad reuse, modification and redistribution.

## Disclaimer

FanOut Query Simulation is an experimental query exploration tool. It is not affiliated with or endorsed by OpenAI, Google or AlsoAsked.

AI engine names identify the concepts represented in the interface and do not imply that live provider integrations are operational.
